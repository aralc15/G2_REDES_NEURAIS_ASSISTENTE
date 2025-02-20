# Configuração do Ambiente para OpenCV, NumPy e MediaPipe
Introdução
Este projeto utiliza as bibliotecas OpenCV, NumPy e MediaPipe para processamento de imagens e detecção de postura em tempo real. Para garantir o funcionamento correto, siga as instruções abaixo para a instalação e importação dessas bibliotecas no IDLE (Python Shell) e Visual Studio Code (VS Code).

Instalação das Bibliotecas
Antes de executar o código, certifique-se de que as bibliotecas estão instaladas no seu ambiente Python. Para isso, utilize os seguintes comandos no terminal ou prompt de comando:

bash
Copiar
Editar
pip install opencv-python numpy mediapipe
Se estiver utilizando um ambiente virtual, ative-o antes da instalação com:

bash
Copiar
Editar
# No Windows (cmd ou PowerShell)
venv\Scripts\activate  

# No macOS/Linux
source venv/bin/activate
Caso precise de versões específicas das bibliotecas para compatibilidade com o sistema operacional ou dependências do projeto, utilize:

bash
Copiar
Editar
pip install opencv-python==<versão> numpy==<versão> mediapipe==<versão>
Para verificar as versões disponíveis, consulte a documentação oficial de cada biblioteca.

Importação no Código
Após a instalação, as bibliotecas podem ser importadas diretamente no seu script Python:

python
Copiar
Editar
import cv2  # OpenCV
import numpy as np  # NumPy
import mediapipe as mp  # MediaPipe
Esses comandos devem funcionar corretamente tanto no IDLE quanto no VS Code, desde que a instalação tenha sido bem-sucedida.

Teste do Código
Para testar o código, foi utilizado o aplicativo Elgato Camera Hub tanto no computador quanto no celular, pois o integrante responsável pelo código não possui uma câmera diretamente ligada ao computador. Esse aplicativo permitiu utilizar a câmera do celular como uma webcam, facilitando o desenvolvimento e os testes do sistema de visão computacional. Caso o usuário também não possua uma webcam física, recomenda-se o uso de aplicativos semelhantes para simular uma câmera no PC.

Solução de Problemas
Caso ocorra algum erro ao importar as bibliotecas, siga estas recomendações:

Verifique a instalação

Execute pip list para conferir se as bibliotecas estão instaladas.
Se não estiverem listadas, reinstale com pip install --upgrade opencv-python numpy mediapipe.
Confirme o ambiente Python

Certifique-se de estar executando o código no mesmo ambiente onde as bibliotecas foram instaladas.
Verifique a compatibilidade do OpenCV

Em alguns sistemas, pode ser necessário instalar pacotes adicionais, como:
bash
Copiar
Editar
pip install opencv-contrib-python
Isso adiciona funcionalidades extras ao OpenCV, que podem ser exigidas em determinados projetos.
Consulte a documentação oficial

OpenCV
NumPy
MediaPipe
Se os problemas persistirem, considere reinstalar o Python e configurar um novo ambiente virtual para evitar conflitos entre versões de bibliotecas.

O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO, EXPRESSA OU IMPLÍCITA, INCLUINDO MAS NÃO SE LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO, ADEQUAÇÃO A UM DETERMINADO FIM E NÃO INFRINGÊNCIA. EM NENHUM CASO OS AUTORES OU DETENTORES DE DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR QUALQUER RECLAMAÇÃO, DANOS OU OUTRA RESPONSABILIDADE, SEJA EM AÇÃO DE CONTRATO, TORT OU OUTRA FORMA, DECORRENTE DE, FORA DE OU EM CONEXÃO COM O SOFTWARE OU O USO OU OUTRAS NEGOCIAÇÕES NO SOFTWARE.

Para mais informações sobre a Licença MIT: https://opensource.org/licenses/MIT
