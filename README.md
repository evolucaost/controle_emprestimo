# controle_emprestimo
Descrição do Sistema: ControlaTEC
ControlaTEC é um sistema web completo e robusto, projetado para a gestão e controle do ciclo de vida de equipamentos de informática. A plataforma centraliza o inventário de ativos de TI e gerencia todo o processo de empréstimos e devoluções, substituindo planilhas manuais e processos informais por uma solução segura, rastreável e eficiente.

O sistema foi desenvolvido com uma interface limpa e intuitiva, separada por níveis de permissão para garantir que as operações críticas sejam realizadas apenas por usuários autorizados.

Principais Funcionalidades:

🔐 Segurança e Controle de Acesso
Autenticação Segura: Sistema de login com senhas criptografadas (hashing) e autenticação baseada em Token (JWT) com tempo de expiração.

Níveis de Permissão: Dois níveis de usuário (Administrador e Comum), onde apenas administradores podem gerenciar usuários e realizar operações críticas como editar e excluir equipamentos.

Troca de Senha Obrigatória: Novos usuários criados por um administrador são forçados a definir uma senha pessoal e secreta em seu primeiro acesso.

🖥️ Gerenciamento de Ativos
Cadastro Completo: Formulário detalhado para registrar novos equipamentos com informações como nome, marca, modelo, número de patrimônio e número de série.

Listagem Centralizada: Todos os equipamentos são exibidos em uma tabela principal com informações essenciais, incluindo a situação atual ("Disponível" ou "Emprestado") e o nome do responsável.

Paginação: A lista de equipamentos é paginada para garantir alta performance e uma experiência de usuário fluida, mesmo com um grande volume de itens.

🔄 Fluxo de Empréstimo e Devolução
Registro Completo: Processos claros e distintos para registrar empréstimos e devoluções.

Anexo de Documentos: Suporte para upload de termos de responsabilidade (no empréstimo) e de devolução, garantindo o registro formal de cada transação.

Histórico Detalhado: Cada equipamento possui um histórico completo de todas as suas movimentações, registrando quem foi o responsável, as datas de empréstimo e devolução, e links para os documentos anexados.

⚙️ Administração e Usabilidade
Dashboard de Visão Geral: Tela inicial que apresenta estatísticas importantes (total de itens, disponíveis, emprestados) e uma lista das atividades mais recentes no sistema.

Navegação por Abas: A interface é organizada em seções claras (Dashboard, Gerenciamento de Equipamentos, Gerenciamento de Usuários) para uma navegação intuitiva.

Gerenciamento de Usuários (Admin): Uma área restrita onde administradores podem criar novos usuários (comuns ou admins), editar suas informações e excluí-los do sistema.

Busca e Filtros Dinâmicos: Ferramentas poderosas na tela de gerenciamento para encontrar equipamentos rapidamente por texto ou filtrar por situação (Disponível/Emprestado).

Exportação para Excel: Funcionalidade para exportar a lista de equipamentos (respeitando os filtros aplicados) para um arquivo .xlsx, facilitando a criação de relatórios externos.

Em suma, o ControlaTEC é uma solução completa que traz organização, segurança e total controle sobre os ativos de TI de uma organização.

