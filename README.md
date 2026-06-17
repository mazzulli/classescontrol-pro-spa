# ClassesControl — Landing Page

Site SPA estático para www.classescontrol.com.br

## Como fazer deploy

### Vercel (recomendado)
1. Crie uma conta em https://vercel.com
2. Importe este repositório (GitHub/GitLab/Bitbucket)
3. Framework Preset: **Other**
4. Root Directory: `.`
5. Build Command: *(deixe vazio)*
6. Output Directory: `.`
7. Clique em **Deploy**
8. Nas configurações do projeto, adicione o domínio `classescontrol.com.br`

### Render
1. Crie uma conta em https://render.com
2. New → Static Site
3. Conecte seu repositório
4. Nome: `classescontrol`
5. Publish Directory: `.`
6. Build Command: *(deixe vazio)*
7. Clique em **Create Static Site**
8. Em Settings → Custom Domains, adicione `classescontrol.com.br`

## Estrutura
```
classescontrol/
├── index.html     # Aplicação completa (HTML + CSS + JS inline)
├── vercel.json    # Configuração para Vercel
├── render.yaml    # Configuração para Render
└── README.md
```

## Tecnologias
- HTML5 + CSS3 + JavaScript vanilla (sem dependências)
- Google Fonts: Space Grotesk + Inter
- Canvas 2D API para o orb animado com partículas
- IntersectionObserver para animações on-scroll
- Cursor customizado com efeito glow
- Efeito parallax no mouse
- Animações de contadores
- Card tilt effect 3D
