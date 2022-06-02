
# TurboMind

Easy neural link create!

Crie sua própria rede neural e treinamentos de maneira rápida e descomplicada!
Nossa documentação está disponível em formado de menu Help para windows e PDF!




## Instalação

Baixe nosso pack e importe para sua IDE C#.

```bash
  //Criando uma rede neural
  using TurboMind.MindFactory;

  RedeNeural rede = new(0.005, 1, 1);
  Agente agenteSmith = new("Novo agente","Dominador da Matrix!");

  agenteSmith.InserirRedeNeural(rede);


  //Escola
  DeepLearning deepLearning = new("Treinar agenteSmish", "Treinar Capacidade do agente de se esquivar de balas!");
  deepLearning.ConfigurarFuncaoErro(FuncaoErro.SingleLoss);            
  deepLearning.InserirAmbienteTreinamento(Velocidade.SituacaoProblema(), Velocidade.Gabarito());
  deepLearning.SetupDeTreinamento(5000, true, 5000);

  agenteSmish.InserirMetodologiaDeAprendizado(deepLearning);
  agenteSmish.AutoTreinamento();

  Resposta = agenteSmish. ... 

  

```
    
![App Screenshot](https://i.stack.imgur.com/po840.jpg)

