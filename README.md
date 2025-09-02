## 1. Iniciar uma nova tarefa

- Fazer o “Assign” da tarefa
- Mover a tarefa/issue para a coluna “In Progress”

## 2. Criar o branch da tarefa/issue

- Crie um branch para desenvolver a tarefa a partir do branch dev
- Exemplo para a tarefa/issue23:

```bash
git checkout dev                        # (faz o checkout do branch dev)
git pull                                # (atualiza o branch dev)                          
git checkout -b enhancement/issue23     # (Cria o branch para o issue23)
```

![image](https://github.com/user-attachments/assets/2dad477d-1b8a-4b1b-bcaa-fe45d5e99c8b)

## 3. Atualize os comentários e status da tarefa/issue no GitHub Project

Você deve reportar:

- Travamento ou problemas com a tarefa
- Potenciais melhorias
- Comentários permites
- Links
- Troca de status ou labels
- Marcar os envolvidos nos comentários

## 4. Fazer commits seguindo os padrões de commits:

Veja o link:  [[Padrões de Commit|https://github.com/Lab-Fabrica-de-Software/.github/wiki/Padrões-de-Commit]] 

## 5. Fazer push ao  final do dia ou de uma tarefa

Não esquecer de fazer um push das suas tarefas no final do dia ou quando você achar necessário:
```bash
git push --set-upstream origin enchancement/issue24
```

## 6. Ao finalizar a tarefa:

- Mover a tarefa para a coluna Review
- Fazer o Pull Request para a branch dev

## 7. Verifique depois se o seu pull request foi aceito ou se existem comentários.