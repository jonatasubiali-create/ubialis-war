# 🚀 Como Publicar o Jogo no GitHub Pages em 3 Minutos

Todos os arquivos necessários já estão prontos e organizados nesta pasta (ou no arquivo `Ubialis_WAR_Web_GitHub.zip` na Área de Trabalho).

---

### Passo 1: Criar o Repositório no GitHub
1. Acesse: **[github.com/new](https://github.com/new)** (faça login na sua conta).
2. No campo **Repository name**, digite: `ubialis-war` (ou o nome que preferir).
3. Deixe marcado como **Public** (Público).
4. Clique no botão verde: **Create repository**.

---

### Passo 2: Fazer o Upload dos Arquivos
1. Na página do repositório recém-criado, clique no link **"uploading an existing file"**.
2. Arraste **todos os arquivos desta pasta** para dentro do navegador:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.png`
   - `icon-192.png`
   - `icon-512.png`
   - `icon.ico`
   - `favicon.ico`
   - `.nojekyll` (fundamental para o GitHub Pages não ignorar arquivos ocultos)
3. Na parte inferior, clique no botão verde: **Commit changes**.

---

### Passo 3: Ativar o GitHub Pages
1. No menu superior do seu repositório, clique em ⚙️ **Settings** (Configurações).
2. No menu lateral esquerdo, clique em 🌐 **Pages**.
3. Na seção **Build and deployment > Branch**:
   - Mude de `None` para **`main`** (pasta `/root`).
   - Clique em **Save**.
4. Aguarde cerca de 30 a 60 segundos e recarregue a página.
5. O GitHub exibirá o link público HTTPS do seu jogo no topo:
   `https://<seu-usuario>.github.io/ubialis-war/`

---

### Passo 4: Concluir o Pacote Google Play (.AAB)
Com o seu link no ar, geramos o pacote final `.aab` assinado com o Bubblewrap para enviar diretamente ao Google Play Console!
