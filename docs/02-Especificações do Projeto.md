# Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, foi aplicada a técnica de priorização da Escala de Três Níveis, que busca delimitar o universo de possíveis valores desse atributo para tais possibilidades, de modo que a prioridade seja uniformizada e melhor entendida por todos do time.

Foram estabelecidos os níveis de prioridade de acordo com os dois aspectos principais: importância e urgência. Assim, forma-se um quadrante, capaz de criar prioridades que combinem esses aspectos.

![image](https://user-images.githubusercontent.com/103579574/229512485-da1405c1-c007-4bb0-bffb-1f177a19beb3.png)

## Requisitos Funcionais

| ID      | Descrição do Requisito | Prioridade |
|---------|-----------------------------------------------|-----------|
| RF-001  | Gerar fichas de treino personalizadas com imagens da execução dos exercícios. | ALTA |
| RF-005  | Criar planos alimentares personalizados com base nos objetivos do usuário. | ALTA |
| RF-006  | Oferecer sugestões de treinos e dietas baseadas no histórico e progresso. | ALTA |
| RF-009  | Notificações de lembretes para treinos e refeições. | MÉDIA |
| RF-008  | Sincronização com dispositivos de monitoramento de saúde (smartwatches, smartbands). | MÉDIA |
| RF-002  | Criar playlists musicais baseadas nas preferências do usuário. | BAIXA |
| RF-003  | Permitir medição corporal e exibição de progresso através de gráficos. | BAIXA |
| RF-004  | Analisar fotos de pratos de comida e estimar valores nutricionais. | BAIXA |
| RF-007  | Gerar recomendações de suplementos conforme necessidade do usuário. | BAIXA |
| RF-016  | O aplicativo deve fornecer descrição em áudio dos exercícios para acessibilidade. | BAIXA |
| RF-010  | Integração com redes sociais para compartilhamento de progresso. | BAIXA |
| RF-011  | Gamificação: Recompensas e desafios para manter a motivação. | BAIXA |
| RF-012  | Modo Treinador: Permitir que personal trainers cadastrem alunos e montem planos. | BAIXA |
| RF-013  | Treino ao Vivo: Aulas interativas e transmissões de especialistas. | BAIXA |
| RF-014  | Marketplace: Loja de suplementos e produtos fitness. | BAIXA |
| RF-015  | Detecção de Execução de Exercício: Análise via câmera para corrigir postura. | BAIXA |

## Requisitos Não Funcionais

| ID       | Descrição do Requisito | Prioridade |
|----------|---------------------------------------------|-----------|
| RNF-001  | O aplicativo deve ser responsivo e intuitivo. | ALTA |
| RNF-002  | A IA deve garantir recomendações precisas baseadas em dados confiáveis. | ALTA |
| RNF-005  | Privacidade e segurança de dados conforme LGPD. | ALTA |
| RNF-003  | Alto desempenho para processamento de imagens e análise de dados. | MÉDIA |
| RNF-004  | Armazenamento seguro de informações dos usuários. | ALTA |
| RNF-006  | Suporte multiplataforma (Android e iOS). | BAIXA |
| RNF-007  | Interface amigável para diferentes perfis de usuários. | BAIXA |

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir:

| ID      | Descrição da Restrição |
|---------|-----------------------------------------------|
| RES-001 | O aplicativo deve operar em dispositivos móveis com Android 8+ e iOS 13+. |
| RES-002 | A infraestrutura do aplicativo deve garantir a escalabilidade para um grande número de usuários simultâneos. |
| RES-003 | O aplicativo deve seguir as diretrizes de design da Google Play Store e App Store. |

# Regras de Negócio

## 📊 Personalização Inteligente  
A IA deve considerar peso, altura, idade e objetivo do usuário para criar treinos e dietas personalizadas.  

## 🏋️‍♂️ Execução Correta  
As imagens dos exercícios devem seguir padrões biomecânicos corretos para evitar lesões e garantir a eficácia dos treinos.  

## 🔊 Acessibilidade Inclusiva  
Além das imagens demonstrativas dos exercícios, o aplicativo fornecerá uma descrição em áudio dos movimentos para atender usuários com deficiência visual e dificuldades na leitura.

## ✏️ Ajuste Manual  
O usuário pode modificar treinos e dietas sugeridas de acordo com suas preferências e necessidades.  

## 🍽️ Análise Nutricional Confiável  
A análise de fotos de pratos de comida será baseada em um banco de dados alimentar confiável, garantindo estimativas precisas.  

## 📈 Evolução Contínua  
Os treinos e dietas serão ajustados automaticamente conforme o progresso do usuário para manter a eficácia.  

## 🔒 Segurança e Privacidade  
Os dados dos usuários serão armazenados com segurança e não serão compartilhados sem consentimento.  

