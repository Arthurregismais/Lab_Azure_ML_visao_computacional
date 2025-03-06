# Lab_Azure_ML_visao_computacional

Neste laboratório, faremos uma análise de imagens com o apoio da IA da Azure.

Links úteis:\
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html\ 
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html\
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html\ 

-----

Para darmos início ao experimento, precisamos acessar o site da azure:\
https://portal.azure.com/#home

Em seguida, devemos escolher as opções: Criar Novo Recurso -> Azure AI Services -> Criar. 

Na tela que será aberta, você deve informar o grupo de recursos e o nome desejado. Na opção de Tipo de preço, selecione a primeira e única opção fornecida. Depois marque a caixinha de texto embaixo.

![image](https://github.com/user-attachments/assets/075d7dfe-dc2c-47d9-a4dd-47a046ce83a5)
![image](https://github.com/user-attachments/assets/b980fb8b-2772-482c-a081-592aeca5eb37)

Após isso, clique em Examinar + Criar. 

Com o recurso criado, agora devemos ir para https://portal.vision.cognitive.azure.com/

Acessando com suas credenciais da Microsoft, você será direcionado para uma página contendo diversas opções de utilidades da IA da Azure. Procure pela: Add Captions to Images

![Screenshot 2025-03-06 174649](https://github.com/user-attachments/assets/c671b775-0aef-4225-8c05-5e39b8395cc2)

Dentro dela, você pode utilizar algumas fotos já fornecidas pela Azure ou usar fotos presentes no seu computador para realizar seus experimentos. No caso, utilizei algumas fotos que encontrei na Internet:

![Screenshot 2025-03-06 174034](https://github.com/user-attachments/assets/f2462302-bab1-42df-bcb0-fed84875ddee)

Com sua foto selecionada, a ferramenta rapidamente fará uma análise e informará seu diagnóstico. Você pode também optar por ver o JSON do resultado, como no caso da imagem acima.

Desta forma, é possível utilizar a IA da Azure para realizar diversas diversas funcionalidades, das mais simples como a apresentada acima, quanto mais complexas como realizar resumos de um vídeo apresentado a ela.

Neste repositório, existem duas pastas, input, que são as imagens utilizadas na análise, e output, que são os resultados fornecidos pela ferramenta da Azure.


# Minha opinião após realizar o experimento:
Ao realizar este Lab, percebi o quanto a tecnologia tem avançado, algo como tão complexo detecção de características em imagens, sendo realizado por uma inteligência artificial, realmente é surpreendente. Essas novas ferramentas são muito capazes de nos auxiliar em serviços críticos de nossa sociedade. Imagine como a polícia poderia utilizar uma IA para reconhecer criminosos mais facilmente? Ou como um médico poderia ter diagnósticos mais rapidamente e com mais precisão, ou talvez até apoio de uma Inteligência Artificial em uma cirurgia complexa? 
