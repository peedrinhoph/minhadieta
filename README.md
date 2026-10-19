# Minha Dieta — PWA

Aplicativo estático para planejar dieta por dia da semana e horário. Não usa backend; os dados ficam no `localStorage` do navegador.

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
