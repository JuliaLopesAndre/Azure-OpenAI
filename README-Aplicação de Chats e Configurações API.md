# Aplicação de Chats e Configurações API – Azure OpenAI  

## Modos Suportados  
O **Azure OpenAI** oferece suporte a diversos modos de operação, incluindo:  
- **Chat**– Interação com assistentes virtuais.  
- **Completar**– Geração automática de textos com base em um prompt.  
- **Imagens**– Criação de imagens com **DALL·E**.  
- **Áudio**– Transcrição e síntese de fala.  

## Hands-On: Principais Conceitos  
### **Control Plane** 
Área responsável pelo gerenciamento de **recursos**, incluindo **deployments** e controle de acessos.  

### **Stream**   
Modo que **envia as respostas palavra por palavra**, simulando uma conversa em tempo real, semelhante a um chat contínuo.  

## Gerenciamento de Mensagens no Chat  
Para manter o **contexto de conversação**, é necessário seguir algumas regras:  
- O modelo pode **manter até 10 mensagens** antes de precisar limpar ou substituir dados.  
- Ao exceder esse limite, **duas mensagens antigas devem ser removidas**.  
- Essa substituição gera um **novo System e User Message**, permitindo manter um novo conjunto de 10 mensagens.  

## **Semantic Kernel**  
O **Semantic Kernel** gerencia tudo relacionado ao **código** e à **integração da IA com aplicações**. Ele permite conectar modelos de IA a fluxos de trabalho, otimizando a automação e personalização dos resultados.  
