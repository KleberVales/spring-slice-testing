# 🧪 Spring Slice Testing 

Este projeto demonstra como realizar **Slice Testing** no Spring Boot usando `@WebMvcTest`, carregando apenas a camada **Web** e simulando as demais dependências com `@MockBean`.

---

## 📚 Objetivo
- Testar **somente a camada de Controller** sem inicializar todo o contexto da aplicação.
- Usar **MockMvc** para simular requisições HTTP.
- Simular o comportamento do **ProductService** usando `@MockBean`.

---

## 🏗 Tecnologias Utilizadas
- **Java 21**
- **Spring Boot 3**
- **Spring Web**
- **JUnit 5**
- **MockMvc**
- **Mockito**

---

## 📂 Estrutura de Pastas

```text
spring-slice-testing-demo/
├── build.gradle.kts
├── src
│ ├── main
│ │ └── java/com/example/springslicetest
│ │ ├── SpringSliceTestingDemoApplication.java
│ │ ├── controller/ProductController.java
│ │ ├── entity/Product.java
│ │ ├── service/ProductService.java
│ └── test
│ └── java/com/example/springslicetest
│ └── ProductControllerSliceTest.java
└── src/main/resources/application.properties
```


