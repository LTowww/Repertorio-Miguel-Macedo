Repertório Musical - Miguel Macedo

Aplicação web de repertório musical que permite gerenciar músicas (adicionar, editar, excluir e buscar) com autenticação simples e armazenamento local no navegador.

Funcionalidades:
Área restrita com login por senha;
Adicionar músicas ao repertório;
Editar músicas;
Excluir músicas;
Buscar músicas por nome ou artista;
Armazenamento local com LocalStorage;
Suporte a links de cifra e áudio;
Interface responsiva;

Tecnologias utilizadas:
HTML5;
CSS3;
JavaScript (Vanilla JS);

Autenticação:
O sistema possui uma área restrita para gerenciamento do repertório.
A senha está definida diretamente no código JavaScript:
const PASSWORD = "senhamiguel";

Importante: No momento, este método é apenas para fins educacionais e não é seguro para aplicações reais.

Armazenamento de dados:
Os dados são armazenados no navegador utilizando LocalStorage.
Isso significa que:
Os dados não são compartilhados entre dispositivos;
Não há necessidade de backend;
Limpar o navegador apagará todas as músicas;

Estrutura das músicas:
Cada música cadastrada contém:
Nome da música;
Artista;
Gênero (opcional);
Link da cifra (opcional);
Link de áudio (opcional);

Possíveis melhorias:
Sistema de login seguro com backend;
Integração com banco de dados;
Sincronização entre dispositivos;
Upload de arquivos de áudio;
Criação de playlists;

Autor: 

Miguel Macedo

Instagram: https://www.instagram.com/miguel_flp_/

GitHub: https://github.com/LTowww
