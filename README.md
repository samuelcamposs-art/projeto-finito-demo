# Projeto Finito: demonstração

Projeto de demonstração, sem dados reais.

Todos os pacientes, profissionais, visitas e evoluções deste ambiente são fictícios.
Não usar com dados de pacientes reais.

## Conteúdo
- `index.html`: página mínima com o banner de demonstração.
- Banco de dados: Supabase, projeto `projeto-finito-demo`, região `sa-east-1` (São Paulo).
- Credenciais: não estão neste repositório. Ver a seção de segurança abaixo.

## Segurança
- Nenhuma chave secreta deve ser versionada.
- Chaves de serviço (service role) ficam apenas em variáveis de ambiente do Netlify.
- A chave pública (anon) pode ser usada no front-end, pois o acesso aos dados é controlado por RLS.
