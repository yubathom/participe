<template>
<div id="app" @keyup.esc="fechaTudo">
	<div :class="{ desligado: interruptor }" id="interruptor" ref="interruptor" @click="fechaTudo"></div>
	<Cabecalho></Cabecalho>
	<MenuLateral></MenuLateral>
	<router-view name="Home"></router-view>
	<router-view name="Anhembi2"></router-view>
	<router-view name="ArcoPinheiros"></router-view>
	<router-view name="WifiLivreSP"></router-view>
	<router-view name="DigilabLivreSP"></router-view>
	<router-view name="VidaSegura"></router-view>
	<router-view name="VilaLeopoldina2"></router-view>
	<router-view name="PortalPrefeitura"></router-view>
	<router-view name="GovernoAberto"></router-view>
	<router-view name="ConcessaoMartinelli"></router-view>
	<router-view name="ArcoPinheiros2"></router-view>
	<router-view name="SetorCentral2"></router-view>
	<router-view name="PlanoCicloviario"></router-view>
	<router-view name="ParqueMinhocao"></router-view>
	<router-view name="MinutaArcoPinheiros"></router-view>
	<Rodape></Rodape>
</div>
</template>

<script>
import Cabecalho from '@/components/Cabecalho'
import MenuLateral from '@/components/MenuLateral'
import Rodape from '@/components/Rodape'

export default {
	name: 'Participe',
	components: {
		Cabecalho,
		MenuLateral,
		Rodape
	},
	computed: {
		interruptor () { return this.$store.state.luzApaga } },
	created () {
		let app = this
		window.addEventListener('keydown', function (event) {
			if (event.ctrlKey && event.code === 'KeyP') {
				app.$store.dispatch('imprime')
			}
		})
	},
	mounted () { document.getElementById('carregando').classList.add('some') },
	updated () { this.$refs.interruptor.style.height = this.$el.clientHeight + 'px' },
	methods: {
		fechaTudo () {
			if (this.$store.state.menuToggle || this.$store.state.apoioToggle) {
				this.$store.state.menuToggle = false
				this.$store.state.apoioToggle = false
				this.$store.state.luzApaga = false
			};
			document.body.style.overflow = document.body.style.overflow === '' ? 'hidden' : ''
		}
	}
}
</script>

<style lang="scss">
@import 'assets/icones/participe.css';
@import 'assets/icones/participe.custom.scss';
@import 'variables';

* { box-sizing: border-box; };
html { margin: 0; padding: 0; };

body {
	font-family: $font-stack;
	color: #333;
	font-size: 16px;
	line-height: 1.6;
	margin: 0;

	a { text-decoration: none; color: $vermelho; };

	a:hover { text-decoration: underline; };
};

i[class] {
	-webkit-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
	&::after { visibility: hidden; }
	&:hover { cursor: default; };
};

div#interruptor {
	position: absolute;
	transition: all ease-in-out .2s;
	z-index: 4;

	&.ligado { background: rgba(0, 0, 0, 0); };

	&.desligado {
		background: rgba(0, 0, 0, .72);
		display: block;
		width: 100%;
		height: unset;
	};
};

#carregando.some { height: 0; }

#btn-sw-update {
	width: 100%;
	height: 65px;
	display: flex;
	align-items: center;
	text-align: center;
	justify-content: center;
	background-color: #ef8383;
	a {
		color: white;
		&:hover {
			text-decoration: none;
		}
	}
	transition: all ease-in-out .2s;
	&:hover {
		cursor: pointer;
		background-color: #EB5757
	}
}

@media print {
	body { background-color: $preto; }
	div#app { background-color: white; width: 210mm; }
	div#interruptor { display: none; }
	div#carregando { display: none; }
}

</style>
