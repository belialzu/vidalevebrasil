# Instruções para Implantação no GitHub Pages

Este arquivo contém instruções detalhadas para implantar o site VidaLeve Brasil no GitHub Pages.

## Passos para Implantação

1. Crie um novo repositório no GitHub:
   - Acesse https://github.com/new
   - Nome do repositório: vidalevebrasil
   - Descrição: Site de afiliados para produtos de emagrecimento e suplementos da ClickBank
   - Escolha "Public" (necessário para GitHub Pages gratuito)
   - Clique em "Create repository"

2. Faça upload dos arquivos para o GitHub:
   - Após criar o repositório, execute os seguintes comandos:
   ```
   git remote add origin https://github.com/SEU_USUARIO/vidalevebrasil.git
   git branch -M main
   git push -u origin main
   ```
   - Substitua "SEU_USUARIO" pelo seu nome de usuário do GitHub

3. Configure o GitHub Pages:
   - Acesse as configurações do repositório (Settings)
   - Role até a seção "GitHub Pages"
   - Em "Source", selecione "main" como branch
   - Clique em "Save"

4. Acesse seu site:
   - Após alguns minutos, seu site estará disponível em:
   - https://SEU_USUARIO.github.io/vidalevebrasil/

## Personalização de Domínio (Opcional)

Para usar um domínio personalizado (como vidalevebrasil.com.br):

1. Compre um domínio em um registrador de sua preferência (Registro.br, GoDaddy, etc.)
2. Nas configurações do GitHub Pages, adicione seu domínio personalizado
3. Configure os registros DNS conforme as instruções do GitHub

## Manutenção e Atualizações

Para atualizar o site no futuro:

1. Faça as alterações necessárias nos arquivos locais
2. Execute os comandos:
   ```
   git add .
   git commit -m "Descrição das alterações"
   git push origin main
   ```

O GitHub Pages atualizará automaticamente seu site após cada push.
