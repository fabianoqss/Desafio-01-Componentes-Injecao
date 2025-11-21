# 🧩 Desafio 01 -- Componentes e Injeção de Dependência (Spring Boot)

Este repositório contém a solução do **Desafio 01**, parte do curso de
_Java + Spring Boot_.\
O objetivo desta atividade é introduzir conceitos fundamentais do
ecossistema Spring, como:

- **Componentes (@Component)**
- **Serviços (@Service)**
- **Controladores (@RestController)**
- **Injeção de Dependência (@Autowired)**
- **IoC -- Inversão de Controle**

## 🎯 Objetivo do Desafio

O desafio consiste em criar uma pequena aplicação Spring Boot para
entender:

- Como declarar classes como componentes gerenciados pelo Spring.
- Como o mecanismo de **IoC Container** funciona.
- Como funciona a **Injeção de Dependência automática**.
- Como um serviço pode ser injetado em outro componente.

## 🛠️ O que foi implementado

- Classe serviço com `@Service`
- Classe componente com `@Component`
- Injeção de dependência com `@Autowired`
- Demonstração de comunicação entre componentes Spring

## ▶️ Como executar

1.  Clone o projeto:

```
git clone https://github.com/fabianoqss/Desafio-01-Componentes-Injecao
```
2.  Acesse o diretório:


```
cd desafio-01
```
3.  Execute:

```
mvn spring-boot:run
```
## 📚 Conceitos aprendidos

- Inversão de Controle (IoC)
- Container e ciclo de vida de Beans
- Autowired e resolução automática de dependências
- Component Scan

## 📦 Tecnologias

- Java 17+
- Spring Boot 3+
- Maven
