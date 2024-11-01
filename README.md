## Database-Oscar

# Quantas vezes Natalie Portamn ganhou?
```sql
SELECT COUNT(*) * FROM indicados_ao_oscar WHERE = "Name" like = "%Natalie Portamn%";
```

**Resposta**: 3 vezes.
# Quantos Oscars Natalie Portman ganhou?
```sql
SELECT * FROM indicados_ao_oscar WHERE nome_do_indicado like "%Natalie Portman%" AND vencedor = "true";
```

**Resposta**: 1 vez.

# Amy Adams já ganhou algum Oscar?
```sql
SELECT * FROM indicados_ao_oscar WHERE nome_do_indicado like "%Amy Adams%";
```

**Resposta**: Não

# A série de filmes Toy Story ganhou um Oscar em quais anos?
```sql
SELECT * FROM indicados_ao_oscar WHERE nome_do_filme like "%Toy Story%" AND vencedor = "true";
```

**Resposta**: Em 2011 e 2020

# A partir de que ano que a categoria "Actress" deixa de existir?
```sql
SELECT * FROM indicados_ao_oscar WHERE categoria = "ACTRESS" ORDER BY ano_cerimonia DESC;
```

**Resposta**: 1977

# Quem ganhou o primeiro Oscar para Melhor Atriz? Em que ano?
```sql
SELECT * FROM indicados_ao_oscar WHERE vencedor = "true" AND categoria = "ACTRESS";
```

**Resposta**: Janet Gaynor

# Na campo "Vencedor", altere todos os valores com "true" para 1 e todos os valores "false" para 0.

# Em qual edição do Oscar "Crash" concorreu ao Oscar?

# O filme Central do Brasil aparece no Oscar?

# Inclua no banco 3 filmes que nunca foram nem nomeados ao Oscar, mas que merecem ser.

# Denzel Washington já ganhou algum Oscar?

# Quais os filmes que ganharam o Oscar de Melhor Filme?

# Bonus: Quais os filmes que ganharam o Oscar de Melhor Filme e Melhor Diretor na mesma cerimonia?

# Bonus: Denzel Washington e Jamie Foxx já concorreram ao Oscar no mesmo ano?

