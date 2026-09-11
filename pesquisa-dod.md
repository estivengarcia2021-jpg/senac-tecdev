**Definition of Done (DoD)** é um conjunto claro e compartilhado de critérios que um item de trabalho (como uma *User Story* ou tarefa) deve atender para ser considerado 100% concluído e pronto para envio à produção.

No Scrum e em metodologias ágeis, a DoD funciona como um acordo de qualidade entre a equipe de desenvolvimento e as partes interessadas (*stakeholders*). Seu principal objetivo é garantir transparência e evitar o falso progresso — garantindo que "pronto" signifique que o código foi testado, integrado e revisado, e não apenas "terminado no meu computador".

---

**Checklist Prático de Definition of Done (DoD)**

1. **Revisão de Código (Code Review)**
* O código foi revisado por pelo menos outro desenvolvedor, atende aos padrões de estilização do projeto e não possui alertas no linter.


2. **Testes Automatizados Passando**
* Testes unitários e de integração foram criados ou atualizados, cobrindo as novas funcionalidades sem quebrar a suíte de testes existente.


3. **Validação de Critérios de Aceite**
* A funcionalidade foi testada manualmente e atende a todos os critérios de aceite definidos na *User Story*.


4. **Documentação Atualizada**
* A documentação técnica (endpoints na API, README ou diagramas) e, se aplicável, as notas de lançamento (*Release Notes*) foram devidamente atualizadas.


5. **Integração e Deploy em Staging**
* As alterações foram mescladas (*merged*) na branch principal (`main`/`develop`) e implantadas no ambiente de testes/homologação sem erros.
