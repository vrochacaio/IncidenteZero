</br>

### <p align=center>INCIDENTES ZERO API

<p align=center>Gerenciador de Incidentes

</br>
</br>
</br>

Esse sistema permite o gerenciamento de incidentes garantindo o cadastro, manutenção e remoção deles por um determinado
usuário a partir de operações REST.

</br>
</br>
</br>

## Construido com

* [Java 11]()
* [Docker]()
* [Spring Boot]()
* [Spring Web MVC]()
* [Spring Data JPA]()
* [Lombok]()
* [H2 DATABASE]()

</br>
</br>
</br>

## Endpoints

#### ```/incidents```

* **POST:** Cadastro de incidentes

  ➜ ```name: String``` @REQUIRED

  ➜ ```description: String``` @REQUIRED

#### ```/incidents/{id}```

* **PUT:** Manutenção de incidentes

  ➜ ```name: String``` @OPTIONAL

  ➜ ```description: String``` @OPTIONAL


* **DELETE:** Remoção de incidentes

</br>
</br>
</br>

## Instalação

### Pré-requisitos

* Java 11
* Maven 3.6

</br>

### Passos

1. Clone o repositório

```
$ git clone https://github.com/vrochacaio/IncidenteZero.git
```

2. Instalando com Maven

```
$ mvn clean install
```

</br>

### Uso

1. Rodando o projeto com docker compose
```
$ docker compose up -d
```

2. Apos a conclusao do comando acima, pode-se fazer requisições HTTP nos endpoints existentes: [ENDPOINTS](https://github.com/vrochacaio/IncidenteZero#endpoints)

</br>

### License
Distributed under the MIT License. See [LICENSE](https://github.com/vrochacaio/IncidenteZero/blob/main/LICENSE) for more information.

</br>

### Contato
Caio Rocha - [@CODIGO.ROCHA](https://linktr.ee/vrocha.caio)
Project Link: https://github.com/vrochacaio/IncidenteZero
