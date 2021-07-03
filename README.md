# TV Encryption

_Prototype of a key management system for live video stream encryption._

These repositories were created as part of a bachelor thesis at [ZHAW Winterthur](https://www.zhaw.ch). Therefore the code is not actively being maintained.

To get an overview of the systems, it is beneficial to read the [thesis](Documents/Bachelor_Thesis_TV_Encryption.pdf).

## Documents
- [Bachelor_Thesis_TV_Encryption.pdf](Bachelor_Thesis_TV_Encryption.pdf)
- [Defense_Presentation.pdf](Defense_Presentation.pdf)

## Repositories
- [key_server](https://github.com/TV-Encryption/key_server)
- [keygenerator](https://github.com/TV-Encryption/keygenerator)
- [fairplay_server](https://github.com/TV-Encryption/fairplay_server)
- [FairplayKSM](https://github.com/TV-Encryption/FairplayKSM)
- [Demo-App](https://github.com/TV-Encryption/Demo-App)

## Deployments

In contrast to developement deployments, production deployments have different needs and we therfore have separate deployment configurations for them. In theory they should just pull a docker image produced by CI but since these are just simple example configs, they just build locally.

- [key_server-deployconf](https://github.com/TV-Encryption/key_server-deployconf)
- [keygenerator-deployconf](https://github.com/TV-Encryption/keygenerator-deployconf)
- [fairplay_server-deployconf](https://github.com/TV-Encryption/fairplay_server-deployconf)