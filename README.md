# Aula Git 

![](/gif/git.png)

## Comandos git:

- **Git init**: Inicia o projeto git.

- **Git status**: Nos mostra o status desse repositório.
    * A nossa Branch;
    * Mudanças para serem commitados.

- **Git log**: Nos mostra a linha de tempo de commit.

    ![](/gif/1.PNG)

- **Git log --oneline**: Mostra a linha do tempo reduzida.

    ![](/gif/5.PNG)

- **Git add**: Adiciona os arquivos no modo storage (staging).
    * git add < file>;
    * git add . (tudo).

- **Git rm --cached < file>**: Remove o arquivo que adicionamos.

- **Git diff**: Mostra as diferenças que teve no work para o commit.

- **Git Config**: Para configurar.
    * git config user.name "JeanCigoli";
    * git config user.email "jeancigoli30@gmail.com".

- **Git commit -m "Mensagem"**: Para fazer o commit.

- **Git checkout < identificação do commit >**: Muda para onde o Head vai apontar, podendo voltar a versão anterior.

- **Git checkout < branch>**: Para mudar de branch.

- **Arquivo .gitignore**: Para colocar os arquivos que serão ignorados.