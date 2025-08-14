# 🧪 Spring Slice Testing 

Este projeto demonstra como realizar **Slice Testing** no Spring Boot usando `@WebMvcTest`, carregando apenas a camada **Web** e simulando as demais dependências com `@MockBean`.

---

## 📚 Objetivo
- Testar **somente a camada de Controller** sem inicializar todo o contexto da aplicação.
- Usar **MockMvc** para simular requisições HTTP.
- Simular o comportamento do **ProductService** usando `@MockBean`.

---

