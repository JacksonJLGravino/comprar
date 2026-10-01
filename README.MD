# Comprar

Aplicativo mobile para organizar uma lista de compras. Adicione itens, acompanhe o que ainda precisa ser comprado e marque como concluído o que já foi resolvido.

![Thumbnail do aplicativo Comprar](./Thumbnail.png)

## Funcionalidades

- Adicionar itens à lista de compras.
- Separar itens pendentes e concluídos por filtros.
- Marcar um item como concluído ou voltar para pendente.
- Remover itens individualmente ou limpar a lista inteira.
- Manter os dados salvos localmente no dispositivo.

## Tecnologias

- React Native
- Expo
- TypeScript
- AsyncStorage
- Lucide React Native

## Como executar

Pré-requisitos: Node.js e npm instalados. Para executar em um dispositivo físico, instale também o Expo Go.

```bash
npm install
npm start
```

Com o servidor Expo iniciado, escaneie o QR code com o Expo Go ou escolha uma plataforma no terminal. Também é possível iniciar diretamente com:

```bash
npm run android
npm run ios
npm run web
```

## Dados

Os itens são armazenados localmente no dispositivo usando AsyncStorage. Eles não são sincronizados entre dispositivos.
