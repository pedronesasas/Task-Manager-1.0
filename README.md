# 📝 Lista de Tarefas com Subtarefas (SPA)

Uma aplicação simples e minimalista para gerenciamento de tarefas, permitindo adicionar **tarefas principais** e **subtarefas** usando um formato estruturado em múltiplas linhas.

Desenvolvido com **HTML + TailwindCSS + JavaScript puro**.

---

## 🚀 Funcionalidades

* Adição de várias tarefas de uma vez
* Subtarefas associadas a cada tarefa
* IDs definidos pelo próprio usuário
* Checkbox para tarefas e subtarefas
* Expandir/Recolher subtarefas
* Exclusão em cascata
* Ordenação automática por ID
* Interface minimalista e responsiva

---

## ✍️ Formato de entrada

Você pode colar várias tarefas de uma vez seguindo o padrão:

```
[ID],[Título],[Prazo],[Prioridade],[Detalhes]
-Subtarefa 1
-Subtarefa 2
-Subtarefa 3

[ID],[Título],[Prazo],[Prioridade],[Detalhes]
-Subtarefa 1
-Subtarefa 2
```

### Exemplo:

```
142,Voxuy,14h dia 13,alta,fazer junto do joão
-Conferir automação
-Testar link de checkout personalizado

143,TAP,hoje,alta,call de alinhamento com o lucas
-Buscar doc modelo no drive 
-Call com o lucão
```

---

## ▶️ Como usar

1. Cole suas tarefas no campo de texto
2. Pressione **Enter**
3. As tarefas aparecem automaticamente no painel
4. Clique na seta para expandir/recolher subtarefas
5. Clique no “x” para excluir toda a tarefa + subtarefas

---

## 🛠 Tecnologias utilizadas

* **HTML**
* **Tailwind CSS (CDN)**
* **JavaScript (ES6)**
