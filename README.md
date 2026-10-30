# pandemonivm-rpg.github.io
PANDEMONIVM RPG page

## Servir localmente

Execute `python3 serve.py --bind 0.0.0.0 --port 3000` para acesso local e pela rede/Tailscale. O servidor permite somente HTML, CSS, JavaScript e as duas texturas públicas. Usa gzip e ETag para evitar transferir novamente arquivos que não mudaram. Alterações nos arquivos aparecem sem cópia temporária.

As texturas são SVG locais sem filtros procedurais. A tipografia usa fontes instaladas no dispositivo, sem requisições externas.

Verificação: `sh .agents/scripts/check.sh`.

## Contribuir com agentes

Leia [AGENTS.md](AGENTS.md) e a habilidade local [.agents/skills/pandemonivm/SKILL.md](.agents/skills/pandemonivm/SKILL.md).
