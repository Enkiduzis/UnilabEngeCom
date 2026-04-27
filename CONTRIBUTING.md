
# 🤝 Guia de Contribuição

Primeiramente, muito obrigado por querer contribuir com o repositório de **Engenharia da Computação da UNILAB**! 🎉 

Este projeto só funciona porque alunos como você dedicam um tempo para ajudar a comunidade. Não importa se você é do 1º ou do 10º semestre, toda colaboração é bem-vinda (provas, listas, resumos, correções).

Para mantermos a organização e respeitarmos a privacidade de todos, por favor, siga as diretrizes abaixo.

---

## 🛡️ Regra de Ouro: Privacidade (LGPD)
**NENHUM arquivo deve conter dados pessoais de alunos.**
Antes de enviar qualquer documento, você deve **obrigatoriamente**:
1. Apagar ou colocar uma tarja opaca sobre **Nomes** e **Matrículas**.
2. Garantir que o PDF foi "achatado" (ou seja, não é possível copiar o texto escondido atrás da tarja).
> 📖 *Dúvidas? Leia nosso [Guia de Anonimização de Arquivos](./GUIA_ANONIMIZACAO.md).*

---

## 📂 Como enviar seus materiais

Escolha o método que você achar mais fácil:

### Método 1: Sou iniciante (Não sei usar Git)
Se você ainda não domina o Git/GitHub, não tem problema! Você pode enviar os materiais diretamente pelo navegador.

1. Vá até a aba **[Issues](../../issues)** do repositório.
2. Clique no botão verde **New Issue**.
3. Selecione o template **Envio de Material**.
4. Preencha as informações pedidas (Disciplina, Semestre, Professor).
5. Arraste os PDFs anonimizados para a caixa de texto.
6. Clique em **Submit new issue**.
Pronto! Um dos mantenedores do projeto vai baixar seu arquivo e colocar na pasta correta.

### Método 2: Já sei usar Git (Via Terminal)
Se você já manja dos comandos, o fluxo é o clássico *Fork & Pull Request*.

**1. Faça o Fork e Clone**
Crie um *Fork* do projeto para a sua conta e baixe para o seu computador:
```bash
git clone [https://github.com/SEU_USUARIO/NOME_DO_REPO.git](https://github.com/SEU_USUARIO/NOME_DO_REPO.git)
cd NOME_DO_REPO

```
**2. Crie uma Branch**
Use o padrão tipo/disciplina-semestre.
*Tipos:* feat (novo material), fix (correção), docs (documentação).
```bash
git checkout -b feat/calculo1-2023-2

```
**3. Adicione os Arquivos**
Coloque os PDFs na pasta correspondente ao semestre e à disciplina.
> ⚠️ **Atenção à nomenclatura do arquivo:**
> O arquivo DEVE seguir o padrão: Ano_Semestre_Professor_Tipo.pdf
> *Exemplo:* 2023_2_JoaoSilva_Prova_AP1.pdf ou 2024_1_MariaSouza_Lista3.pdf
> 
**4. Faça o Commit e Push**
```bash
git add .
git commit -m "feat: adiciona provas de Cálculo I do professor João"
git push origin feat/calculo1-2023-2

```
**5. Abra o Pull Request**
Volte ao repositório original no GitHub e clique em **Compare & pull request**. Descreva rapidamente o que você está enviando e confirme o checklist de privacidade.
## 🛠️ O que aceitamos?
 * **Provas e Testes:** Preferencialmente em PDF limpo e legível.
 * **Listas de Exercícios:** Em branco ou resolvidas (desde que corretas ou com aviso de que são resoluções de alunos).
 * **Resumos/Notas de Aula:** Materiais de autoria própria feitos para estudo.
 * **Links Úteis:** Indicações de simuladores, softwares ou livros abertos relevantes para as disciplinas (pode adicionar no README de cada semestre).
## 🚫 O que NÃO aceitamos?
 * Materiais com nomes, matrículas ou notas de alunos.
 * Livros piratas (PDFs com direitos autorais restritos).
 * Resoluções de trabalhos/projetos práticos que ainda estão sendo avaliados no semestre atual (não incentivamos plágio).
Em caso de dúvidas, sinta-se à vontade para abrir uma Issue com a label duvida ou procurar os mantenedores. Bons estudos! 🚀