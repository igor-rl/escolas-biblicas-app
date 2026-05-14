# Escolas Bíblicas — App

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/igor-rl/escolas-biblicas-app?style=flat-square&color=blue)](https://github.com/igor-rl/escolas-biblicas-app/releases/latest)

Página de download e releases do aplicativo desktop **Escolas Bíblicas** — ferramenta para gestão de turmas das Escolas Bíblicas Teocráticas das Testemunhas de Jeová.

## 📥 Download

Acesse a página de download ou baixe diretamente pela página de releases:

| Sistema | Arquivo |
|---|---|
| **macOS** (Apple Silicon) | `Escolas-Biblicas-macOS-x.x.x-arm64.dmg` |
| **macOS** (Intel) | `Escolas-Biblicas-macOS-x.x.x-x64.dmg` |
| **Windows** (instalador) | `Escolas-Biblicas-windows-installer-x.x.x.exe` |
| **Windows** (portátil) | `Escolas-Biblicas-windows-portable-x.x.x.exe` |

👉 **[Ver todas as versões](https://github.com/igor-rl/escolas-biblicas-app/releases)**

### macOS

1. Abra o `.dmg` e arraste o app para **Aplicativos**
2. Como o app não é assinado pela App Store, o macOS irá bloqueá-lo na primeira abertura. Para liberar, abra o **Terminal** e rode:

```bash
xattr -rd com.apple.quarantine '/Applications/Escolas Biblicas.app' && open '/Applications/Escolas Biblicas.app'
```

Ou vá em **Ajustes do Sistema → Privacidade e Segurança** e clique em **"Abrir mesmo assim"**.

### Windows

1. Execute o instalador `.exe` e siga os passos
2. O app criará um atalho na Área de Trabalho e no Menu Iniciar
3. Se preferir não instalar, use a versão **portátil** — basta executar o `.exe` diretamente

> Os arquivos `.yml` e `.blockmap` são usados internamente para atualizações automáticas — não é necessário baixá-los.

---

<br/>
<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Igor_Lage-blue?style=social&logo=github)](https://github.com/igor-rl)

</div>
