<template>
	<div class="Apoio">
		<aside :class="{ aberto: apoioToggle }">
			<ul class="tabs">
				<slot name="item1">
					<li>
						<input type="radio" name="tabs" id="item1">
						<label for="item1">Decreto</label>
						<div class="conteudoTab">
							<h1>Decreto Nº 56901 de 29 de março de 2016</h1>
								<p class="caput">Dispõe sobre a elaboração de Projeto de Intervenção Urbana, nos termos do disposto no artigo 134 da Lei nº 16.050 , de 31 de julho de 2014 - Plano Diretor Estratégico – PDE.</p>
								<p>FERNANDO HADDAD, Prefeito do Município de São Paulo, no uso das atribuições que lhe são conferidas por lei,</p>
								<p>D E C R E T A:</p>
								<p>Art. 1º O Projeto de Intervenção Urbana - PIU tem por finalidade reunir e articular os estudos técnicos necessários a promover o ordenamento e a reestruturação urbana em áreas subutilizadas e com potencial de transformação no Município de São Paulo, nos termos do disposto no artigo 134 da Lei nº 16.050 , de 31 de julho de 2014 - Plano Diretor Estratégico - PDE.</p>
								<p>§ 1º O PIU será utilizado para o desenvolvimento dos projetos da Rede de Estruturação e Transformação Urbana, composta pelos seguintes elementos estruturadores do território:</p>
								<p>I - Macroárea de Estruturação Metropolitana;</p>
								<p>II - rede estrutural de transporte coletivo, definidora dos eixos de estruturação da transformação urbana;</p>
								<p>III - rede hídrica e ambiental;</p>
								<p>IV - rede de estruturação local.</p>
								<p>§ 2º O PIU poderá ser implantado por meio de quaisquer instrumentos de política urbana e de gestão ambiental, nos termos do artigo 148 da Lei nº 16.050, de 2014, além de outros deles decorrentes, dentre os quais aqueles constantes do § 5º do artigo 134 da referida lei.</p>
								<p>§ 3º Para os fins deste decreto, consideram-se:</p>
								<p>I - áreas subutilizadas: imóveis que necessitam de mudanças nos padrões de uso e ocupação do solo visando maior aproveitamento da terra urbana, considerados isoladamente ou em conjunto;</p>
								<p>II - áreas com potencial de transformação: áreas urbanizadas que demandam recuperação, reabilitação ou qualificação para aplicação de programas de desenvolvimento urbano, econômico, ambiental ou social, de modo a fomentar:</p>
								<p>a) novas atividades econômicas; e</p>
								<p>b) atendimento às necessidades de habitação e equipamentos sociais para a população.</p>
								<p>Art. 2º Deverão preceder o processo de elaboração do PIU, no mínimo:</p>
								<p>I - diagnóstico da área objeto de intervenção, com caracterização dos seus aspectos socioterritoriais;</p>
								<p>II - programa de interesse público da futura intervenção, considerando a sua diretriz urbanística, viabilidade da transformação, impacto ambiental ou de vizinhança esperado, possibilidade de adensamento construtivo e populacional para a área e o modo de gestão democrática da intervenção proposta.</p>
								<p>§ 1º Uma vez concluídos, os documentos previstos no "caput" deste artigo serão divulgados para consulta pública pelo período mínimo de 20 (vinte) dias.</p>
								<p>§ 2º Findo o prazo para consulta pública e após a análise das sugestões recebidas, o processo administrativo será encaminhado à Secretaria Municipal de Desenvolvimento Urbano - SMDU, para:</p>
								<p>I - análise da adequação da proposta à política de desenvolvimento urbano do Município; e</p>
								<p>II - autorização para elaboração do PIU.</p>
								<p>Art. 3º Uma vez autorizada a elaboração do PIU, a São Paulo Urbanismo - SP-Urbanismo fará a publicação dos seguintes elementos, necessários ao seu desenvolvimento:</p>
								<p>I - definição do perímetro de intervenção;</p>
								<p>II - características básicas da proposta;</p>
								<p>III - fases da elaboração do projeto, obrigatoriamente com mecanismos que assegurem o caráter participativo dessas atividades.</p>
								<p>§ 1º Fica autorizada a promoção de chamamento público para manifestação de interesse na apresentação de projetos.</p>
								<p>§ 2º Deverá constar do edital de chamamento a forma de participação social e os critérios para avaliação das propostas apresentadas.</p>
								<p>Art. 4º O conteúdo final do PIU deverá apresentar:</p>
								<p>I - proposta de ordenamento ou reestruturação urbanística para o perímetro delimitado, com a definição de programa de intervenção, fases de implantação, parâmetros urbanísticos e instrumentos de gestão ambiental necessários;</p>
								<p>II - modelagem econômica da intervenção proposta, considerando especialmente os mecanismos de financiamento e fonte de recursos necessários;</p>
								<p>III - definição do modelo de gestão democrática de sua implantação, privilegiando o controle social e os instrumentos para monitoramento e avaliação dos impactos da transformação urbanística pretendida sobre o desenvolvimento econômico e social da área objeto de estudo;</p>
								<p>IV - elementos complementares necessários, nos termos do artigo 136 da Lei nº 16.050, de 2014.</p>
								<p>Art. 5º A forma final do PIU será encaminhada por SPUrbanismo à SMDU para, estando presentes os elementos necessários, sua disponibilização para consulta pública pelo período mínimo de 20 (vinte) dias, de acordo com o disposto na Lei nº 16.050, de 2014.</p>
								<p>§ 1º Finda a consulta pública, SMDU adotará as seguintes medidas:</p>
								<p>I - elaboração e divulgação de relatório com as contribuições recebidas e as razões para sua incorporação ou não ao texto;</p>
								<p>II - encaminhamento à Chefia do Poder Executivo, com sugestão de:</p>
								<p>a) elaboração do projeto de lei ou edição de decreto, conforme a hipótese cabível; ou</p>
								<p>b) arquivamento da proposta, fundamentadamente.</p>
								<p>Art. 6º A implantação do PIU veiculado por decreto será realizada por intermédio da SP-Urbanismo.</p>
								<p>§ 1º Fica autorizada a SP-Urbanismo a firmar contratos com terceiros para a implantação do PIU, observadas as seguintes regras:</p>
								<p>I - poderão ser alienados:</p>
								<p>a) imóveis próprios da SP-Urbanismo ou desapropriados para fins de utilidade pública;</p>
								<p>b) direitos relativos a imissões na posse decorrentes de desapropriação;</p>
								<p>II - deverá ser estabelecida a obrigação do adquirente atuar conforme o PIU, nos termos em que foi aprovado, sob pena de rescisão do contrato;</p>
								<p>III - na hipótese de alienação dos direitos relativos a imissões na posse decorrentes de desapropriação, o valor mínimo a ser pago pelo adquirente deverá corresponder ao montante despendido pelo Poder Público para obter a imissão na posse, na ação expropriatória, permitido acréscimo de percentual a título de remuneração da SP-Urbanismo, pela estruturação do projeto e pelo risco de arcar com a indenização definitiva;</p>
								<p>IV - o critério para julgamento da licitação da alienação do bem ou dos direitos relativos à imissão na posse poderá ser a maior oferta da remuneração prevista no inciso III deste parágrafo.</p>
								<p>§ 2º Para a implantação do PIU diretamente pela SP-Urbanismo, a empresa poderá promover incorporações imobiliárias, podendo utilizar imóveis próprios, imóveis desapropriados para fins de utilidade pública e direitos relativos a imissões na posse decorrentes de desapropriação.</p>
								<p>Art. 7º Caso sejam necessárias desapropriações para a implantação do PIU, a SP-Urbanismo encaminhará proposta ao Executivo para a edição dos respectivos decretos de utilidade pública.</p>
								<p>Parágrafo único. As desapropriações efetuadas nos termos do "caput" deste artigo serão irretratáveis e irrevogáveis uma vez formalizadas as respectivas imissões na posse, vedado ao Poder Público Municipal, à SP-Urbanismo ou a particulares eventualmente contratados desistir ou renunciar aos direitos e obrigações a elas relativos.</p>
								<p>Art. 8º A SP-Urbanismo poderá iniciar a elaboração de PIU a partir de requerimento apresentado por meio de Manifestação de Interesse Privado - MIP, instruído com os elementos constantes do artigo 3º, observada a realização da consulta pública de que trata o § 1º do artigo 2º, ambos deste decreto.</p>
								<p>Art. 9º Este decreto entrará em vigor na data de sua publicação.</p>
								<p>PREFEITURA DO MUNICÍPIO DE SÃO PAULO, aos 29 de março de 2016, 463º da fundação de São Paulo.</p>
								<p>FERNANDO HADDAD, PREFEITO</p>
								<p>FERNANDO DE MELLO FRANCO, Secretário Municipal de Desenvolvimento Urbano</p>
								<p>FRANCISCO MACENA DA SILVA, Secretário do Governo Municipal</p>
								<p>Publicado na Secretaria do Governo Municipal, em 29 de março de 2016.</p>
						</div>
					</li>
				</slot>
				<slot name="item2"></slot>
			</ul>
		</aside>
		<button @click="abreApoio" :class="{ aberto: apoioToggle }">
			<i class="icon-abrir_esquerda icon"><span>abrir_apoio</span></i>
		</button>
		</div>
</template>

<script>
export default {
	name: 'Apoio',
	data () {
		return {
			aberto: false
		}
	},
	computed: {
		apoioToggle () {
			return this.$store.state.apoioToggle
		}
	},
	methods: {
		abreApoio () {
			if (this.$store.state.apoioToggle) {
				this.$store.state.apoioToggle = false
				this.$store.state.luzApaga = false
			} else {
				this.$store.state.apoioToggle = true
				this.$store.state.luzApaga = true
			};
			document.body.style.overflow = document.body.style.overflow === '' ? 'hidden' : ''
		}
	}
}
</script>

<style lang="scss" scoped>
@import '../variables';

div.Apoio {
	aside {
		position: fixed;
		right: 0;
		top: 0;
		width: 60vw;
		min-width: 300px;
		max-width: 700px;
		height: 100vh;
		min-width: 280px;
		margin: 0;
		background: $cinza-3;
		transform: translateX(100%);
		transition: transform ease-in .2s;
		z-index: 5;
		&.aberto { transform: translateX(0); box-shadow: -8px 0 8px $sombra-2; };
		ul.tabs {
			list-style-type: none;
			padding: 0;
			margin: 0;
			& > li {
				float: left;
				margin: 0;
				padding: 0;
				font-family: $grotesca;
				& > input { display: none; };
				& > label {
					display: inline-block;
					cursor: pointer;
					padding: 20px 2rem;
					opacity: .4;
					font-size: 1rem;
					line-height: 20px;
					transition: all ease-in .1s;
					&:hover { color: #333; };
				};
				& > input:checked + label {
					opacity: 1;
					background-color: $vermelho;
					color: #FFF;
					z-index: 1;
				};
				& > input:checked ~ div.conteudoTab {
					opacity: 1;
					z-index: 2;
				};
			};
			div.conteudoTab {
				/*opacity: 0;*/
				position: absolute;
				left: 0;
				padding: 1.6rem 2rem;
				height: 100%;
				max-height: calc(100vh - 60px);
				min-width: 100%;
				max-width: 100%;
				overflow-y: auto;
				transition: opacity ease-out .2s;
				background: #FFF;
				h1 {
					margin: 0 0 2rem 0;
					padding: 0;
					font-size: larger;
				};
				p.caput {
					font-size: smaller;
					margin: 0 0 2rem 0;
					color: $cinza-1;
				};
				p { padding: 0; }
			};
		};
	};
	button {
		position: fixed;
		padding: 0;
		top: unset;
		bottom: 6rem;
		right: 2rem;
		width: 42px;
		max-height: 42px;
		background: #FFF;
		border-radius: 100%;
		border: 1px solid $cinza-2;
		box-shadow: 0 4px 4px $sombra-4;
		transition: all ease-in .1s;
		display: block;
		font-family: inherit;
		z-index: 1;
		i {
			line-height: 41px;
			height: 1rem;
			width: 1rem;
			font-weight: normal;
			font-size: 22px;
		};
		&:active {
			background: $vermelho;
			color: #FFF;
			border-color: $vermelho;

			&::before { color: $preto; };
		};
		&:hover {
			cursor: pointer;
			&::before { opacity: 1; };
		};
		&::before {
			content: 'Ver material de apoio';
			position: absolute;
			margin: 4px 0 0 -150px;
			line-height: 32px;
			padding: 0 8px;
			border-radius: 10px;
			opacity: 0;
			transition: all ease-in .1s;
			font-size: 14px;
			color: $preto;
		};
	};
	button.aberto {
		transform: rotate(180deg);
		&::before { opacity: 0; };
	};
	@media (max-width: 1200px) {
		aside ul.tabs {
			li label { padding: 8px 12px; };
			div.conteudoTab { max-height: 100%; };
		};
		button::before { display: none; };
	};
	@media print {
		display: none;
	}
};
</style>
