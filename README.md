# Proxy em container realizando redirecionamentos para uma Docker Network diferente
  Exemplo simples do funcionamento de um proxy reverso Nginx em Container Docker, que realiza redirecionamentos para serviços que estão estruturados em `docker-compose.yaml` separados. Alcançabilidade dos serviços ao proxy é graças a uma docker network criada de forma externa ao compose.
  Para bom funcionamento é necessário um DNS estático configurado, redirecionando as urls para o IP da instância que roda o docker daemon.
