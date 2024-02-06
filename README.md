# Controle de Fazendas de Bovinos
O Fazenda Bovina Manager é um sistema desenvolvido em PHP com o framework Symfony, projetado para facilitar o controle eficiente de uma fazenda de bovinos. Com funcionalidades que vão desde o cadastro de veterinários até a geração de relatórios importantes, o sistema visa simplificar a gestão diária e a tomada de decisões estratégicas.

## O que o sistema oferece?
Cadastro de Veterinários: Registro de informações sobre os veterinários, incluindo nome e CRMV, garantindo que haja apenas um veterinário com o mesmo CRMV.

Cadastro de Fazendas: Gerencia informações essenciais sobre as fazendas, como nome, tamanho em hectares, responsável e associação a veterinários.

Cadastro do Gado da Fazenda: Mantem detalhes sobre cada cabeça de gado, incluindo código, produção de leite, consumo de ração, peso, data de nascimento e associação à fazenda.

Regras de Negócio: O sistema incorpora regras como limite de animais por hectare, restrições na duplicidade de informações e critérios para listagem de animais aptos para abate.

Relatórios Estratégicos: Gere relatórios importantes, como animais abatidos, produção total de leite por semana, consumo total de ração por semana e animais jovens que consomem mais de 500Kg de ração por semana.

## Como Iniciar
### Clone o Repositório:
```
git clone https://github.com/seu-usuario/fazenda-bovina-manager.git
```

### Instale as Dependências:
```
cd fazenda-bovina-manager
composer install
```
### Configure o Ambiente:

Copie o arquivo .env.example para .env e configure-o conforme suas necessidades, especialmente as configurações do banco de dados.
### Execute as Migrações:

```
php bin/console doctrine:migrations:migrate
```
### Inicie o Servidor Symfony:

```
symfony serve
```
### Acesse o Sistema:
Abra seu navegador e acesse http://localhost:8000.
