# chatbraille

### Chat para auxiliar deficientes visuais a converterem palavras comuns no formato Braille

🚀 Este projeto foi insperado na Imersão de Gen AI da Alura e no Projeto Social Enxergando o Futuro https://enxergandoofuturo.com.br, que sou volutário e disponibilizamos uma plataforma para o ensino do método Braille básico para pessoas com deficiência visual. Já impactamos a vida de mais de 400 pessoas através da nossa plataforma, atendendo alunos do Brasil, EUA, Cabo Verda, Suiça, Maçambique, Portugal entre outros.

📋 Pré-requisitos
Ter uma API_KEY do google.generativeai
Executar no Google Colab

🔧 Como Executar
Após abrir o aqruivo chatbraille.ipynb no Google Colab, você deverá informar sua API_KEY ou usar sua chave secreta já salva no Colab
API_KEY = userdata.get('secretName')
genai.configure(api_key=API_KEY)
Após estes passos é so executar e será aberto um chat, onde você informa a palabra que deseja ver na estrutura Braille ou digite Encerrar chat para finalizar.

⚙️ Projeto MVP
Devido ao curto tempo de preparação e desenvolvimento, considero o projeto chatbraille na etapa de MVP, pois muitas coisas novas serão implementadas para auxiliar nossos alunos e admiradores do Braille.

🔩 Foram feitos vários testes com palavras e frases, utilizando letras números e caracteres especiais, mas ainda precisam ser refinados.

📦 Implantação
Foi carregado um arquivo com letras, números e caracteres especiais em Braille, baseado na língua portuguesa do Brasil.
Transformado em Dataframe
Gerado Embeddings para consulta semântica
Utilização de recursos de chat para auxiliar o usuário.

🛠️ Construído com
Google colab
Linguagem Python
Utilizando Gemini como suporte
GenerativeAi do Google
aistudio.google.com

📌 Versão
Novas versões serão lançadas para implementação de entrada da pesquisa com o microfone e resultado em áudio, assim, estaremos tratando a acessibilidade das pessoas com deficiência visual.

🎁 Expressões de gratidão
Sou grato a Alura pela oportunidade na imersão e grato ao Projeto Enxergando o Futuro, onde estamos disponibilizando mais uma ferramenta para que nossos alunos possam reforçar o aprendizado do método Braille.
