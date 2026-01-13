💱 Conversor de Moedas - Real para Dólar 💰
📋 Descrição
Este é um programa simples em C# que converte valores de Reais (R$) para Dólares (USD) 🇧🇷➡️🇺🇸, aplicando uma taxa de processamento e gerando um identificador único para cada transação! 🎯
✨ Funcionalidades

👤 Entrada personalizada do nome do usuário
💵 Conversão de moeda com cotação configurável
💳 Taxa de processamento de 1% aplicada automaticamente
🔢 ID único de transação gerado para cada operação
📊 Relatório detalhado com todas as informações da conversão

🚀 Como Usar
Pré-requisitos 📦

✅ .NET SDK instalado (versão 5.0 ou superior recomendada)
✅ Visual Studio, Visual Studio Code ou qualquer IDE C# compatível
✅ Terminal/Console para execução

Executando o Programa 🏃‍♂️

Clone ou baixe este arquivo 📥
Abra o terminal na pasta do projeto 📂
Compile o programa:

bash   csc Program.cs

Execute o programa:

bash   Program.exe
```
   *(No Linux/Mac, use `mono Program.exe`)*

### Exemplo de Uso 💡
```
Digite seu nome: João
Digite o valor em Reais (R$): 1000

--- RESULTADO DA CONVERSÃO ---
ID da Transação: João-45823
Valor original: R$ 1000.00
Valor após taxa (1%): R$ 990.00
Valor convertido: $ 170.69
Cotação utilizada: R$ 5.80
⚙️ Configurações
📈 Alterar a Cotação do Dólar
No código, localize a linha:
csharpdouble cotacaoDolar = 5.80;
Altere o valor 5.80 para a cotação desejada! 💹
💰 Alterar a Taxa de Processamento
No código, localize a linha:
csharpvalorReais *= 0.99; // Taxa de 1%

Para 2%: use 0.98
Para 0.5%: use 0.995
Para sem taxa: use 1.0 🎁

🔍 Detalhes Técnicos
RecursoDescrição🎲 Geração de IDNúmero aleatório entre 10000-99999🔢 Precisão2 casas decimais (:F2)📝 EntradaAceita números decimais🎯 Taxa padrão1% (0.99 multiplicador)
🐛 Possíveis Melhorias

 🌐 Integração com API de cotação em tempo real
 💾 Salvar histórico de transações em arquivo
 🔒 Validação de entrada de dados
 🌍 Suporte para múltiplas moedas
 📱 Interface gráfica (GUI)
 🔐 Criptografia do ID de transação

⚠️ Observações Importantes

⚡ A cotação está fixa no código - atualize manualmente!
🔄 O programa não valida entradas inválidas (ex: letras no valor)
🎲 O ID gerado é pseudoaleatório - não use em produção sem melhorias
💡 Para uso educacional e demonstrativo

👨‍💻 Autor
Desenvolvido com ❤️ para aprendizado de C# e conversão de moedas!
📄 Licença
Este projeto é livre para uso educacional! 🎓✨

⭐ Dica: Favorite este projeto se foi útil! 🌟
🤝 Contribuições são bem-vindas! Sinta-se à vontade para melhorar o código! 💪
