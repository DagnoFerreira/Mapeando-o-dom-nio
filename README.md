# Mapeando-o-dom-nio
Mapeando o domínio

Baseado na conversa entre o desenvolvedor e o especialista de domínio, podemos identificar as seguintes entidades de domínio e casos de uso para o sistema de gerenciamento de estoque.

### **Entidades de domínio:**
1. **Produto:**
   - Atributos:
     - Número de identificação único.
     - Tamanho.
     - Cor.
     - Quantidade em estoque.
   
2. **Estoque:**
   - Atributos:
     - Quantidade atual de produtos.
     - Quantidade mínima de estoque definida.
   
3. **Venda:**
   - Atributos:
     - Quantidade vendida.
     - Preço unitário.
     - Produto vendido.
   
4. **Histórico de Vendas:**
   - Atributos:
     - Registro de vendas passadas.
     - Período de vendas (data).
   
5. **Alerta:**
   - Atributos:
     - Tipo de alerta (quantidade mínima de estoque).
     - Método de envio (e-mail, notificação no sistema).
   
6. **Pedido de Compra:**
   - Atributos:
     - Produto solicitado.
     - Quantidade solicitada.
     - Fornecedor.
     - Status do pedido (em andamento, entregue, etc.).
   
7. **Fornecedor:**
   - Atributos:
     - Nome.
     - Informações de contato.
     - Prazos de entrega.
   
8. **Tendência de Estoque:**
   - Atributos:
     - Histórico de quantidade de estoque ao longo do tempo.
     - Previsão de reposição de estoque.

### **Casos de Uso:**
1. **Rastrear Produto:**
   - Atribuir número de identificação único.
   - Registrar informações adicionais como tamanho e cor.
   - Visualizar movimentação do produto no estoque.
   
2. **Definir Quantidade Mínima de Estoque:**
   - Configurar a quantidade mínima para cada produto.
   - Monitorar o estoque em tempo real e comparar com a quantidade mínima definida.
   
3. **Gerar Alerta de Estoque:**
   - Enviar alertas via e-mail ou notificações no sistema quando o estoque de um produto atingir a quantidade mínima definida.
   
4. **Visualizar Histórico de Vendas e Estoque:**
   - Consultar vendas passadas.
   - Verificar o lucro gerado por produto.
   - Analisar tendências de vendas e estoque para tomar decisões de compra.
   
5. **Gerar Ordens de Compra Automáticas:**
   - Criar ordens de compra automaticamente com base na quantidade mínima de estoque e tendências de vendas.
   
6. **Integrar com Fornecedores:**
   - Enviar informações de pedido automaticamente para os fornecedores.
   - Receber atualizações automáticas sobre os prazos de entrega dos fornecedores.
   
Essas entidades e ações formam a base para o desenvolvimento do sistema de gerenciamento de estoque que o especialista de domínio está buscando.
