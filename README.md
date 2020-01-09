# InstaClone

### Clone do feed do Instagram

---

Exemplo do funcionamento
[![Image from Gyazo](https://i.gyazo.com/d1ac16b09351cb9db39bae289365fc30.gif)](https://gyazo.com/d1ac16b09351cb9db39bae289365fc30)

---

## Como rodar no seu computador:


1. Node
- Entre na pasta "node"
- Rode ```yarn install```
  - Entre na pasta "src"
  - Mude a conexão do mongoose para algum servidor mongo( local ou um cluster no mongodb atlas ). O servidor padrão será desligado.[![Image from Gyazo](https://i.gyazo.com/f4cc16d3f6fbf56d0f887d68be71fc45.png)](https://gyazo.com/f4cc16d3f6fbf56d0f887d68be71fc45)
  - Volte para "node"
- Rode ```yarn dev``` e o servidor será iniciado

2. React
- Entre na pasta "reactclient"
- Rode ```yarn install```
- Rode ```yarn start```
- No seu navegador, insira a url: ```localhost:3000```

3. Usando
- Clique na câmera, preencha o formulário e envie para criar um post
- Clique no coração em algum post para dar um like nele

Lembrando que após o servidor Node estiver iniciado as atualizações no feed ocorrem automaticamente, sem necessidade de recarregar a página.
