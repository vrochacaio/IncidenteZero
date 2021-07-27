### <p align=center>INCIDENTES ZERO API
<p align=center>Gerenciador de Incidentes

</br>
</br>
</br>

Esse sistema permite o gerenciamento de incidentes garantindo o cadastro, manutenção e remoção deles por um determinado usuário a partir de operações REST.

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
  > ```name: String``` @REQUIRED

  > ```description: String``` @REQUIRED

* **PUT:** Manutenção de incidentes
  > ```idIncident: int``` @REQUIRED

  > ```name: String``` @OPTIONAL

  > ```"description: String" ``` @OPTIONAL

* **DELETE:** Remoção de incidentes
  > ```idIncident: int ``` @REQUIRED

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