Visão Geral do Projeto: Detecção Unificada de Lixo
Este projeto apresenta uma solução de visão computacional que utiliza um modelo do Roboflow para identificar diversos tipos de resíduos como uma única classe genérica: "Lixo". O objetivo é simplificar a detecção, independentemente do tipo específico de material (plástico, papel, metal, etc.), focando na presença de descarte inadequado.

# Como Funciona?
A solução é construída em torno de um modelo de detecção de objetos hospedado no Roboflow. Em vez de treinar o modelo para diferenciar entre classes específicas de lixo (como garrafa PET, lata de alumínio, papelão), o processo de anotação e treinamento foi unificado. Isso significa que todas as imagens de diferentes tipos de lixo, provenientes de vários conjuntos de dados ou modelos, foram mapeadas para uma única classe de saída: "Lixo".

Quando uma nova imagem é processada, o modelo retorna a identificação de "Lixo".

# Principais Características

Modelo Roboflow: https://universe.roboflow.com/odontoprev-ky4br/lixo-com-impacto-ambiental
Modelos usados como base (modelo TACO atualizado por em tempo real por API): https://github.com/wimlds-trojmiasto/detect-waste

# Tecnologias Utilizadas
Foram usadas as tecnologias: YOLOv8 e Roboflow
