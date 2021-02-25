# Ambiente de Produção Windows


Para quem estiver no Windows e está tendo problemas para definir a variável `NODE_ENV` no script `"test"`, segue os seguintes passos:  

>  Instale o pacote [cross-env](https://www.npmjs.com/package/cross-env) para lidar com as variáveis ambiente, o comando é: `yarn add cross-env -D` ou `npm install cross-env -D`

>  Altere o script `"test"` no arquivo package.json para o seguinte: `"test": "cross-env NODE_ENV=test jest"`