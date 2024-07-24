# Especificações do Projeto

## Perfis de usuários


<table>
<tbody>
<tr>
<th colspan="2">Perfil 01: Jovem adulto de 16 a 24 </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Jovens em busca de desenvolvimento pessoal
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
 1. Encontrar um hobby gratuito. <br>
 2. Encontrar uma forma melhor para organizar a rotina. <br>
 3. Entrar ambiente que facilite sair do sedentarismo. <br>
 4. Realizar atividades que ajudam a lidar com a ansiedade. <br>
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<th colspan="2">Perfil 02: Adulto de 30 a 50 anos </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Adultos em busca de desenvolvimento pessoal
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
1. Encontrar maneiras de equilibrar a vida profissional e lazer.  <br>
2. Encontrar uma forma melhor para organizar a rotina. <br>
3. Entrar ambiente que facilite sair do sedentarismo. <br>
4. Realizar atividades que ajudam a lidar com a ansiedade. <br>
5. Entrar uma plataforma que ajude a melhorar a produtividade no trabalho. <br>
6. Encontrar maneiras de implementar rotinas de autocuidado. <br>

</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<th colspan="2">Perfil 03: Adulto sênior 60+ anos</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Pessoas buscando manter a mente e o corpo ativos
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
1. Entrar ambiente que facilite sair do sedentarismo.  <br>
2. Encontrar uma plataforma que ajude a realizar atividades que desenvolvem a mente.  <br>
3. Encontrar maneiras de implementar rotinas de autocuidado. <br>
4. Encontrar meios para combater isolamento social. <br>
</td>
</tr>
</tbody>
</table>

      
## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:


|Eu como …`QUEM`    | QUERO/PRECISO ... `FUNCIONALIDADE`                                             |PARA ... `MOTIVO/VALOR`                 |
|--------------------|--------------------------------------------------------------------------------|----------------------------------------|
|Jovem adulto      |poder me cadastrar e fazer login na plataforma para acessar seus recursos | poder realizar os desafios e organizar uma rotina |
|Jovem adulto     | quero poder editar meus dados pessoais na plataforma  | poder apresentar minhas necessidades de acordo com meu perfil  |
|Jovem adulto|quero poder filtrar desafios que irão agregar à minha rotina, tanto física quanto mentalmente, para melhorar meu bem-estar| personalizar meus interesses na plataforma de forma organizada  |
|Adulto| quero poder ver imagens relacionadas a cada desafio na plataforma   |para poder me orientar melhor durante cada passo do desafio |
|Adulto | quero poder me inscrever nos desafios que me interessam na plataforma  |para poder preservar meus gostos e proporcionar uma avaliação positiva |
|Adulto|quero poder ver o nível de dificuldade de cada desafio listado na plataforma para selecionar aqueles que correspondem ao meu nível de habilidade. | para poder evoluir gradativamente, não extrapolando meu limite e consequentemente perdendo o interesse nas tarefas do desafio.  |
|Jovem adulto | quero poder ver a descrição do desafio quando escolhido |  para facilitar meu engajamento no desafio                |
|Adulto sênior | quero poder receber lembretes da plataforma para completar os desafios nos quais me propus  | para eu poder garantir um compromisso com aquele desafio|
|Adulto sênior |quero poder acompanhar meu progresso em cada desafio  | para me manter motivado e focado em alcançar meus objetivos |
|Jovem adulto | Quero que a plataforma mostre quando eu concluir um desafio  | para ter uma noção de como estou evoluindo  |
|Adulto Sênior | quero poder avaliar os desafios que iniciei usando um sistema de classificação por estrela | para fornecer feedback e ajudar outros usuários e desenvolvedores.  |


## Requisitos

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01| O sistema deve permitir o cadastro e login na plataforma. | ALTA | 
|RF-02| O sistema deve permitir que o usuário faça mudanças nos seus dados pessoais  | ALTA | 
|RF-03| O sistema deve ter categorias entre os desafios entre físicos e mentais.   | ALTA |
|RF-04| O sistema deve apresentar uma imagem relacionada a cada desafio.    | BAIXA |
|RF-05| O sistema deve permitir inscrição nos desafios.  | ALTA |
|RF-06| O sistema deve mostrar nível de dificuldade dos desafios entre fácil, médio e avançado.    | BAIXA |
|RF-07| O sistema deve fornecer uma descrição do desafio e primeiro dia do desafio.    | MÉDIA |
|RF-08| O sistema deve enviar lembretes aos usuários para completarem o desafio.    | MÉDIA |
|RF-09| O sistema deve fornecer aos usuários histórico do progresso no desafio.   | MÉDIA |
|RF-10| O sistema deve mostrar a conclusão dos desafios  | ALTA |
|RF-11| O sistema deve permitir ao usuário fazer avaliações de desafios utilizando de 1 a 5 estrelas.  | MÉDIA |

**Prioridade: Alta / Média / Baixa.  

### Requisitos Não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| O sistema deve exigir senha com no mínimo 6 caracteres sendo 1 maiúsculas, 1 minúsculas e 1 caracteres especiais(@,#,$,&,*,etc) | MÉDIA | 
|RNF-02| Ter responsividade para diferentes dispositivos como notebook, smartphone.  | ALTA | 
|RNF-03| Limitar o acesso a no máximo 3 desafios simultâneos por usuário.  | MÉDIA | 
|RNF-04| Ter compatibilidade com as versões mais recentes do Google Chrome, Firefox, Microsoft Edge.  | ALTA | 
|RNF-05| A aplicação deve utilizar as cores verde e branco em seu design.  | ALTA | 

**Prioridade: Alta / Média / Baixa.
