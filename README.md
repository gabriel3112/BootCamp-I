# BootCamp-I
# Adiciona detalhes no README principal
cat << 'EOF' >> README.md

## Seções
- `/projetos-academicos`: Trabalhos de cursos e faculdade.
- `/projetos-pessoais`: Aplicações e projetos próprios.
- `/docs`: Apresentações e certificados.
EOF

# Envia a nova alteração
git add README.md
git commit -m "docs: detalha as seções no README principal"
git push origin main