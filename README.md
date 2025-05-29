# Docker - Curso

## Fundamentos

### 1 Introdução

1. Docker e um pouco de história
2. Características (efemeridade, portabilidade, consistência, isolamento, gerenciamento)
3. Comparativo com outros métodos
4. Casos de uso (desenvolvimento, teste, produção, microsserviços)
5. Imagens
6. Layers (Camadas de imagem)
7. Comandos Essenciais (run, ps, stop, start, rm, images, pull, rmi, info)
8. Tags
9. Ecossistema (Docker Hub, Git Hub Container Registry, Artifact Registry, Container Registry privado)

## 2 Construindo Imagens

1. Hello world (FROM, RUN, COPY, CMD)
2. Aprofundando o Hello world (ADD, ENTRYPOINT)
3. Hello world web (WORKDIR, EXPOSE)
4. Variáveis de Ambiente (ENV)
5. Gerenciamento de Dependências (RUN)
6. Melhores Práticas para produtividade
7. Minimizando o tamanho da imagem (multi-stage builds)
8. Cache do Docker: aproveitando o cache para acelerar a construção
9. Segurança: evitando informações sensíveis no Dockerfile

## 3 Persistência de Dados

1. Volumes
2. Bind mounts
3. Named volumes
4. Anonymous volumes

## 4 Redes

1. O que são redes Docker?
2. Rede padrão (bridge)
3. Redes personalizadas
4. Expondo portas e mapeando contêineres
5. Port forwarding
6. Mapeando portas do container para o host.
7. DNS e Service Discovery

## 5 Segurança

1. Verificando vulnerabilidades nas imagens
2. Escaneamento de imagens com ferramentas como Clair ou Trivy
3. Usuários e privilégios
4. Executando contêineres com usuários não-root
5. Definindo permissões e restrições
6. Utilizando redes Docker para isolar contêineres
7. Configurando firewalls e regras de acesso
8. Utilizando variáveis de ambiente seguras

## 6 Docker Compose

1. Princípios de orquestração de múltiplos contêineres
2. Estrutura do docker-compose.yml
3. Variáveis de ambiente
4. Dependências entre serviços
5. Gerenciando Multi-Container Applications (up, down, build, logs)

## 7 Docker Swarm

1. Orquestração de contêineres em escala
2. Arquitetura do Docker Swarm (Managers, Workers, Swarm Mode)
3. Criando um cluster Docker Swarm
4. Orquestrando containers em múltiplos hosts
5. Escalando aplicações Docker
6. Load Balancing
