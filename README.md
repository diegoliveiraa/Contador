# Contador

Este é um projeto em **Java** que recebe dois números inteiros do usuário e imprime a contagem entre eles. Se o primeiro número for maior que o segundo, uma exceção personalizada é lançada.

## 🛠️ Tecnologias Utilizadas
- Java
- Scanner (para entrada de dados)
- Exceções personalizadas
- IntelliJ IDEA (IDE recomendada)

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/diegoliveiraa/Contador.git
   ```

2. **Acesse o diretório do projeto:**
   ```sh
   cd Contador
   ```

3. **Compile o código:**
   ```sh
   javac -d out src/org/example/Contador.java
   ```

4. **Execute o programa:**
   ```sh
   java -cp out org.example.Contador
   ```

## 📌 Funcionalidades
- Solicita dois números inteiros do usuário.
- Exibe a contagem entre os números informados.
- Lança uma exceção personalizada caso o primeiro número seja maior que o segundo.

## 📖 Exemplo de Uso
**Entrada no terminal:**
```
Digite o primeiro parâmetro
2
Digite o segundo parâmetro
5
```

**Saída esperada:**
```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
```

Caso o primeiro número seja maior que o segundo:
```
Digite o primeiro parâmetro
10
Digite o segundo parâmetro
5
```
**Saída esperada:**
```
O segundo parâmetro deve ser maior que o primeiro
```

## 🔥 Melhorias Futuras
- Adicionar suporte para entrada de múltiplos pares de números.
- Criar uma interface gráfica para melhor interação.
- Melhorar as mensagens de erro e validação de entrada.

## 📌 Autor
Desenvolvido por [Diego Oliveira](https://github.com/diegoliveiraa).

