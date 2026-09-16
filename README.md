# hub

Página única (`index.html`, estático, sem build) com cards que linkam para
os 4 dashboards da Pós-Graduação em Medicina — SLMandic, cada um hospedado
no seu próprio repositório/GitHub Pages:

- `Dashboard-de-NPS-Pacientes-Cl-nicas-P-s-M-dica` — NPS de pacientes
- `agendas-pac-real` — Dashboard Triagem (ConsultaJá)
- `csat` — CSAT Pós Med (Indecx)
- `agendas_pgmed` — Acompanhamento Semanal de Práticas

Não tem pipeline nem dado próprio — só os links. Pra atualizar (novo
dashboard, texto, cor), edite `index.html` direto e publique:

```
git add index.html
git commit -m "Atualiza hub"
git push
```
