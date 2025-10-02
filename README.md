# 📚 biblioteca-operativa_Aureo

Repositorio técnico con más de 50 libros modularizados, vinculados por bloques temáticos y ejes transversales. Cada módulo tiene trazabilidad viva, estado de lectura, y vinculación con ejecución real.

---

## 🔍 Buscador semántico por concepto

```python
def buscar_modulo_por_concepto(concepto):
    diccionario = {
        "reversión": [
            "Bigalow_CandlestickPatterns",
            "Farley_MasterSwingTrader",
            "Bougies_Japonaises_Cafedelabourse_2014",
            "CandlestickBible_KohanFx"
        ],
        "latencia": [
            "BarryJohnson_DMA",
            "Chan_AlgorithmicTrading_Wiley2013",
            "Vorobioff_Procesamiento_Senales_Redes_UTN_2021"
        ],
        "elasticidad": [
            "VanTharp_RiskPsychology",
            "Farley_MasterSwingTrader",
            "Chan_AlgorithmicTrading_Wiley2013"
        ],
        "control adaptativo": [
            "Vorobioff_Procesamiento_Senales_Redes_UTN_2021",
            "Chan_AlgorithmicTrading_Wiley2013"
        ],
        "modularización emocional": [
            "VanTharp_SuperTrader_Expanded"
        ],
        "ejecución en tiempo real": [
            "Vorobioff_Procesamiento_Senales_Redes_UTN_2021",
            "Chan_AlgorithmicTrading_Wiley2013",
            "CandlestickBible_KohanFx"
        ],
        "estructura visual": [
            "Bougies_Japonaises_Cafedelabourse_2014",
            "Beyond_Candlesticks_Nison_1994",
            "CandlestickBible_KohanFx"
        ],
        "riesgo": [
            "VanTharp_RiskPsychology",
            "Chan_AlgorithmicTrading_Wiley2013",
            "BarryJohnson_DMA"
        ]
    }
    return diccionario.get(concepto.lower(), "No hay módulos vinculados")
