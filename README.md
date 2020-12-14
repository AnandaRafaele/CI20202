![CI](https://github.com/samuelclerod/CI20202/workflows/CI/badge.svg?branch=master)

# Projeto Github Actions

Esse projeto tem o objetivo de ensinar Continous Integration para a turma de Engenharia de Software II da Unijuazeiro.

## Tarefas a serem implementas no CI

- [x] fazer o checkout do projeto no CI
- [x] fazer a configuração do ambiente (versão do node e instalação das dependencias)
- [x] executar os testes
- [x] quando enviado para o master, fazer o build do projeto
- [x] disponibilizar o relatório de cobertura de testes e build ao fim do workflow
- [x] quando enviado para o master, fazer a implantação do projeto no [link](http://ci2020-samuelclerod.surge.sh/)

## Scripts Disponíveis

Na raiz do projeto você poderá executar:

### `npm start`

Para executar a aplição em modo de desenvolvimento.\
Acesse [http://localhost:3000](http://localhost:3000) para visualizar no navegador.

A página deverá recarregar a cada edição.\
Você também poderá ver erros de `lint` no console.

// TODO traduzir a partir daqui.

### `npm test`

Inicia o executor de teste no modo de observação interativo.\
Veja a seção sobre [rodando testes](https://facebook.github.io/create-react-app/docs/running-tests) para mais informações.

### `npm run build`

Compila o aplicativo para produção na pasta `build`.\
Ele "embrulha" (bundles) corretamente o React no modo de produção e otimiza o build para o melhor desempenho.

A compilação é reduzida e os nomes dos arquivos incluem os hashes.\
Seu aplicativo está pronto para ser implantado!

Veja a seção sobre [deployment](https://facebook.github.io/create-react-app/docs/deployment) para mais informações.

### `npm run eject`

**Note: Essa operação não pode ser cancelada! Uma vez que você utilizar esse comando: `eject`, você não poderá voltar atrás!**

Se você não estiver satisfeitx com a ferramenta de buid e escolhas de configuração, você pode rodar o comando `eject` a qualquer momento. Este comando removerá a dependência de compilação única de seu projeto.

Isso copiará todos os arquivos de configuração e as dependências transitivas (webpack, Babel, ESLint, etc) diretamente no seu projeto, dessa forma você terá total controle sobre eles. Todos os comando com exceção do `eject` continuarão a funcionar, mas irão apontar para os scripts copiados para que você possa ajustá-los.

Você nunca vai precisar usar o `eject`. O conjunto de recursos selecionados é adequado para implantações pequenas e médias, e você não deve se sentir obrigadx a usar essas funções. No entanto, entendemos que essa ferramenta não será útil se você não tiver como personalizá-la quando estiver prontx para isso.

## Aprenda mais

Você pode aprender mais em: [Documentação para criar uma App em React](https://facebook.github.io/create-react-app/docs/getting-started).

Para aprender React, confira a [documentação React](https://reactjs.org/).

### Divisão de código

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analisando o tamanho do Bundle

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Fazer uma Aplicação Web Progressiva (Progressive Web App - PWA)

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Configurações avançadas

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` falha ao minificar

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
