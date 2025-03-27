# Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, foi aplicada a técnica de priorização da Escala de Três Níveis, que busca delimitar o universo de possíveis valores desse atributo para tais possibilidades, de modo que a prioridade seja uniformizada e melhor entendida por todos do time.

Foram estabelecidos os níveis de prioridade de acordo com os dois aspectos principais: importância e urgência. Assim, forma-se um quadrante, capaz de criar prioridades que combinem esses aspectos.

![image](https://user-images.githubusercontent.com/103579574/229512485-da1405c1-c007-4bb0-bffb-1f177a19beb3.png)

## Requisitos Funcionais

| ID      | Descrição do Requisito | Prioridade | Categoria |
|---------|-----------------------------------------------|-----------|-----------|
| RF-001  | Gerar fichas de treino personalizadas com imagens da execução dos exercícios. | ALTA | R2 (Importante e Urgente) |
| RF-005  | Criar planos alimentares personalizados com base nos objetivos do usuário. | ALTA | R2 (Importante e Urgente) |
| RF-006  | Oferecer sugestões de treinos e dietas baseadas no histórico e progresso. | ALTA | R2 (Importante e Urgente) |
| RF-009  | Notificações de lembretes para treinos e refeições. | MÉDIA | R3 (Não tão Importante, mas Urgente) |
| RF-008  | Sincronização com dispositivos de monitoramento de saúde (smartwatches, smartbands). | MÉDIA | R3 (Não tão Importante, mas Urgente) |
| RF-003  | Permitir medição corporal e exibição de progresso através de gráficos. | MÉDIA | R3 (Não importante, mas urgente) |
| RF-002  | Criar playlists musicais baseadas nas preferências do usuário. | BAIXA | R1 (Importante, mas Não Urgente) |
| RF-004  | Analisar fotos de pratos de comida e estimar valores nutricionais. | BAIXA | R4 (Não tao mportante e Não Urgente) |
| RF-007  | Gerar recomendações de suplementos conforme necessidade do usuário. | BAIXA | R4 (Não tao mportante e Não Urgente) |
| RF-016  | O aplicativo deve fornecer descrição em áudio dos exercícios para acessibilidade. | BAIXA | R1 (Importante, mas Não Urgente) |
| RF-010  | Integração com redes sociais para compartilhamento de progresso. | BAIXA | R4 (Não Importante e Não Urgente) |
| RF-011  | Gamificação: Recompensas e desafios para manter a motivação. | BAIXA | R4 (Não Importante e Não Urgente) |
| RF-012  | Modo Treinador: Permitir que personal trainers cadastrem alunos e montem planos. | BAIXA | R4 (Não Importante e Não Urgente) |
| RF-013  | Treino ao Vivo: Aulas interativas e transmissões de especialistas. | BAIXA | R4 (Não Importante e Não Urgente) |
| RF-014  | Marketplace: Loja de suplementos e produtos fitness. | BAIXA | R4 (Não Importante e Não Urgente) |
| RF-015  | Detecção de Execução de Exercício: Análise via câmera para corrigir postura. | BAIXA | R4 (Não Importante e Não Urgente) |
| RF-016  | Envio automático de dicas diárias sobre treino e saúde (Estilo: Você Sabia?) | BAIXA | R4 (Não Importante e Não Urgente) |

## Requisitos Não Funcionais

| ID       | Descrição do Requisito | Prioridade | Categoria |
|----------|---------------------------------------------|-----------|-----------|
| RNF-001  | O aplicativo deve ser responsivo e intuitivo. | ALTA | R2 (Importante e Urgente) |
| RNF-002  | A IA deve garantir recomendações precisas baseadas em dados confiáveis. | ALTA | R2 (Importante e Urgente) |
| RNF-005  | Privacidade e segurança de dados conforme LGPD. | ALTA | R2 (Importante e Urgente) |
| RNF-003  | Alto desempenho para processamento de imagens e análise de dados. | MÉDIA | R3 (Não tão Importante, mas Urgente) |
| RNF-004  | Armazenamento seguro de informações dos usuários. | ALTA | R3 (Não tão Importante, mas Urgente) |
| RNF-006  | Suporte multiplataforma (Android e iOS). | BAIXA | R1 (Importante, mas Não Urgente) |
| RNF-007  | Interface amigável para diferentes perfis de usuários. | BAIXA | R1 (Importante, mas Não Urgente) |
## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir:

| ID      | Descrição da Restrição |
|---------|-----------------------------------------------|
| RES-001 | O aplicativo deve operar em dispositivos móveis com Android 8+ e iOS 13+. |
| RES-002 | A infraestrutura do aplicativo deve garantir a escalabilidade para um grande número de usuários simultâneos. |
| RES-003 | O aplicativo deve seguir as diretrizes de design da Google Play Store e App Store. |

# Regras de Negócio

### 📊 Personalização Inteligente  
A IA deve considerar peso, altura, idade e objetivo do usuário para criar treinos e dietas personalizadas.  

### 🏋️‍♂️ Execução Correta  
As imagens dos exercícios devem seguir padrões biomecânicos corretos para evitar lesões e garantir a eficácia dos treinos.  

### 🔊 Acessibilidade Inclusiva  
Além das imagens demonstrativas dos exercícios, o aplicativo fornecerá uma descrição em áudio dos movimentos para atender usuários com deficiência visual e dificuldades na leitura.

### ✏️ Ajuste Manual  
O usuário pode modificar treinos e dietas sugeridas de acordo com suas preferências e necessidades.  

### 🍽️ Análise Nutricional Confiável  
A análise de fotos de pratos de comida será baseada em um banco de dados alimentar confiável, garantindo estimativas precisas.  

### 🔒 Segurança e Privacidade  
Os dados dos usuários serão armazenados com segurança e não serão compartilhados sem consentimento.  

