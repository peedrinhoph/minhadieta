# Minha Dieta — PWA

Aplicativo estático para planejar dieta por dia da semana e horário. Não usa backend; os dados ficam no `localStorage` do navegador.

## Publicar no GitHub Pages
1. Crie um repositório GitHub.
2. Envie `index.html`, `manifest.webmanifest`, `sw.js` e `icon.svg` para a raiz do repositório.
3. Vá a **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch principal e a pasta `/ (root)`.
5. Aguarde a publicação e abra o endereço HTTPS fornecido pelo GitHub Pages.

## Instalar no celular
- **iPhone:** abra o site no Safari → Compartilhar → **Adicionar à Tela de Início**.
- **Android:** abra no Chrome → menu ⋮ → **Instalar app** ou **Adicionar à tela inicial**.

## Recursos
- Visualização por dia da semana e refeições por horário.
- Cadastro, edição e exclusão de refeições.
- Campos de alimentos/porções e macros (kcal, proteína, carboidratos, gorduras).
- Marcação de refeições consumidas por dia.
- Metas diárias editáveis.
- Exportação/importação de backup JSON.
- PWA com service worker para cache offline após a primeira visita.
- Todos os dados ficam no navegador local. Exporte o JSON para transferir entre aparelhos ou prevenir perda de dados.

## Observação
Os valores nutricionais do cardápio inicial são estimativas. Ajuste conforme os rótulos, as quantidades reais e orientação profissional. A importação de JSON substitui os dados existentes depois de pedir confirmação.
