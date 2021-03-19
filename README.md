# 1 - yarn install
# 2 - yarn start

se quiser testar local apenas o front só usar as variaveis de ambiente pois já fiz o deploy da API no heroku configura dessa maneira abaixo

``` bash 
REACT_APP_URL=http://localhost:3000
REACT_APP_API_URL=https://pokemon-api-react-back.herokuapp.com/
NODE_ENV=development

