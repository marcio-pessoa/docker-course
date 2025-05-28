# Docker - Curso

## Fundamentos

### 1 Introdução

- O que é Docker?
- Um pouco de história
- Características (efemeridade, portabilidade, consistência, isolamento, gerenciamento)
- Comparativo com outros métodos
- Casos de uso (desenvolvimento, teste, produção, microsserviços)
- Imagens
- Layers (Camadas de imagem)
- Comandos Essenciais (run, ps, stop, start, rm, images, pull, rmi, info)
- Tags
- Ecossistema (Docker Hub, Git Hub Container Registry, Artifact Registry, Container Registry privado)

## 2 Construindo Imagens

- Hello world (FROM, RUN, COPY, CMD)
- Aprofundando o hello world (ADD, ENTRYPOINT)
- Hello world web (WORKDIR, EXPOSE)
- Variáveis de Ambiente (ENV)
- Gerenciamento de Dependências (RUN)
- Melhores Práticas
- Minimizando o tamanho da imagem (multi-stage builds)
- Cache do Docker: aproveitando o cache para acelerar a construção
- Segurança: evitando informações sensíveis no Dockerfile

## 3 Persistência de Dados

- Volumes
- Bind mounts
- Named volumes
- Anonymous volumes

## 4 Redes

- O que são redes Docker?
- Rede padrão (bridge)
- Redes personalizadas
- Expondo portas e mapeando containers
- Port forwarding
- Mapeando portas do container para o host.
- DNS e Service Discovery

## 5 Segurança

- Verificando vulnerabilidades nas imagens
- Escaneamento de imagens com ferramentas como Clair ou Trivy
- Usuários e privilégios
- Executando containers com usuários não-root
- Definindo permissões e restrições
- Utilizando redes Docker para isolar containers
- Configurando firewalls e regras de acesso
- Utilizando variáveis de ambiente seguras

## 6 Princípios de orquestração

- Múltiplos Containers
- Estrutura do docker-compose.yml
- Variáveis de ambiente
- Dependências entre serviços
- Gerenciando Multi-Container Applications (up, down, build, logs)

## 7 Orquestração de Containers em escala

- Arquitetura do Docker Swarm (Managers, Workers, Swarm Mode)
- Criando um cluster Docker Swarm
- Orquestrando containers em múltiplos hosts
- Escalando aplicações Docker
- Load Balancing
