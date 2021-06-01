# Acerca

El proyecto integrado se basó en generar dos modelos para predecir todo el flujo vehicular de 2020 y entender cuándo es que ya no se usará más el método de pago efectivo en el Peaje Illia. Este análisis se puede extrapolar a los otros peajes ya que vimos en el Proyecto 3 que las tendencias y la manera de comprortarse de las series de los distintos peajes era similar. 

Para eso hicimos un modelo multivariable de LSTM con Keras con dos variables: `cantidad_pasos` y `dias`. Luego volvimos a nuestro modelo inicial del proyecto 3 de regresión RandomForest para evaluar cual performaba mejor. 

A veces un modelo simple con data bien preprocesada es mejor que un modelo complejo con mala data. 
