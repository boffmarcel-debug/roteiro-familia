# NYC 2026 · roteiro da família

App do roteiro de Nova York (10 a 17 de outubro de 2026), pronto para o GitHub Pages.

## O que tem neste pacote

- `index.html`: o app.
- `sw.js`: faz o app funcionar sem internet depois da primeira abertura.
- `manifest.webmanifest` e os ícones `.png`: permitem instalar o app na tela inicial.
- `leaflet.js` e as fontes `.woff2`: o mapa e as fontes ficam junto do app, sem depender de outros sites.

Não renomeie os arquivos e envie todos juntos, na raiz do repositório.

## Como publicar no GitHub Pages

1. Entre no GitHub e crie um repositório novo (**New repository**). Use um nome discreto, por exemplo `roteiro-familia`.
2. No plano gratuito, o repositório precisa ser **público**. Qualquer pessoa com o link verá hotel e datas, então compartilhe o link só com a família. O app pede aos buscadores para não indexar a página.
3. No repositório, clique em **Add file → Upload files**, arraste **todos os arquivos** desta pasta (não a pasta em si) e clique em **Commit changes**.
4. Vá em **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, depois a branch **main** e a pasta **/ (root)**, e clique em **Save**.
5. Em um ou dois minutos, o endereço aparece no topo dessa página, no formato `https://SEU-USUARIO.github.io/roteiro-familia/`.

## Como instalar no celular

- **iPhone:** abra o endereço no Safari, toque em Compartilhar e depois em **Adicionar à Tela de Início**.
- **Android:** abra no Chrome, toque no menu ⋮ e em **Instalar app** (ou **Adicionar à tela inicial**).

Abra o app uma vez com internet. Depois disso, roteiro, mapa e metrô funcionam mesmo sem conexão. Rotas do Google Maps, Uber, links externos e a previsão do tempo precisam de internet.

## Como atualizar

Para trocar o app por uma versão nova, faça **Add file → Upload files** com os arquivos novos (mesmos nomes) e **Commit changes**. Com internet, o celular pega a versão nova ao abrir o app.

## Bom saber

- Marcações, notas, horários e ingressos ficam salvos em cada celular. O que foi marcado no link do claude.ai não passa para este endereço.
- A previsão do tempo vem do Open-Meteo, aparece até 16 dias antes de cada data e se atualiza a cada 3 horas quando há internet.
- Horários, funcionamento de lugares e serviços do metrô podem mudar. Confirme nos sites oficiais antes de ir.
