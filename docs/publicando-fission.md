## Publicando a aplicação na plataforma da Fission
Para publicar o app na [Fission](https://fission.codes/), você só precisa seguir alguns passos:

* Clonar este projeto e mudar a branch para `dev`
* Verificar que o `Main.elm` foi alterado para `Flatris.elm` devido a um problema no código original
* Iniciar o serviço do [IPFS](https://ipfs.io/) com `ipfs daemon &` em outra aba
* Executar `fission app-init` dentro da pasta do projeto
* Executar `fission up`, e pronto, ta publicado!


## TODO
    Implementar um "Leaderboard" para que os usários com conta na Fission possam comparar seus resultados
    