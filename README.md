# Flash Light

Um aplicativo simples de lanterna para React Native que permite ligar e desligar o flash do seu dispositivo através de toque na tela ou agitação do celular.

## Sobre o Projeto

Este aplicativo foi desenvolvido em React Native usando Expo e oferece uma interface minimalista para controlar a lanterna do dispositivo. O diferencial é que você pode alternar a lanterna não apenas tocando na tela, mas também chacoalhando o celular.

## Funcionalidades

- Ligar/desligar a lanterna através de toque
- Alternar lanterna com shake (agitar o celular)
- Interface limpa e intuitiva
- Mudança visual clara entre os estados ligado/desligado
- Animação suave de transição

## Tecnologias Utilizadas

- [React Native](https://reactnative.dev/) - Framework para desenvolvimento mobile
- [Expo](https://expo.dev/) - Plataforma para desenvolvimento React Native
- [React Navigation](https://reactnavigation.org/) - Navegação entre telas
- [react-native-torch](https://github.com/britishcouncil/react-native-torch) - Controle do flash
- [react-native-shake](https://github.com/lucasferreira/react-native-shake) - Detecção de movimento shake

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:

- [Node.js](https://nodejs.org/en/) (versão 12 ou superior)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [Git](https://git-scm.com)

Para testar o app, você também precisará:

- Um dispositivo físico Android ou iOS com o app Expo Go instalado
- Ou um emulador Android/iOS configurado

## Instalação

```bash
# Clone este repositório
git clone https://github.com/nevesmarcos42/Flash-Ligth.git

# Acesse a pasta do projeto
cd Flash-Ligth

# Instale as dependências
npm install
```

## Executando o Aplicativo

```bash
# Inicie o servidor Expo
npm start

# Ou especificamente para Android
npm run android

# Ou para iOS
npm run ios
```

Após executar o comando, um QR Code aparecerá no terminal ou no navegador. Escaneie-o com:

- **Android**: App Expo Go
- **iOS**: Câmera nativa do iPhone

## Como Usar

1. Abra o aplicativo no seu dispositivo
2. Toque no ícone da lâmpada para ligar/desligar a lanterna
3. Ou simplesmente agite o celular para alternar
4. O fundo da tela mudará de branco (ligado) para preto (desligado)

## Estrutura do Projeto

```
Flash-Ligth/
├── assets/
│   └── icons/          # Ícones da lâmpada acesa e apagada
├── src/
│   ├── pages/
│   │   └── FlashLigth/ # Tela principal do app
│   └── routes/         # Configuração de rotas
├── App.js              # Componente raiz
├── package.json        # Dependências do projeto
└── README.md           # Este arquivo
```

## Contribuindo

Contribuições são sempre bem-vindas! Se você tem alguma sugestão para melhorar o app, sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## Licença

Este projeto é livre para uso pessoal e educacional.

## Autor

Desenvolvido por **Marcos Neves**

- GitHub: [@nevesmarcos42](https://github.com/nevesmarcos42)

---

Se este projeto te ajudou de alguma forma, considere dar uma estrela!
