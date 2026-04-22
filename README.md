# Analysis_channel_YTB
Is possible to live from YTB with a small channel?

| Requirements | Skills |
|--------------|--------|
| - `python3.10`<br> - `Pandas`<br> - `Numpy`<br> - `excel`<br> - `Bigquery`<br>  |  - `Data extracting`<br> - `Data cleaning and transformation`<br> - `Data wrangling`<br> - `API`<br> - `Data Anlysis` 

## Introduction
The data was collected from the channel [@cintikahome](https://www.youtube.com/@cintikahome). This analysis aims to estimate whether a small youtube channel can, on average, generate half of the minimum wage in Spain.

## Analysis

### 1. Evolution by video type
We categorized the videos into long-form and short-form videos. We observe 8-10 average videos per month after the end of 2023. We cant se a consistent publication of shorts videos. 


<img src="https://github.com/rleonardg/Anlysis_channel_YTB/blob/main/assets/normal_videos_evolution.png">
<img src="https://github.com/rleonardg/Anlysis_channel_YTB/blob/main/assets/short_videos_evolution.png">

### 2. Median duration
Has been calculated for long videos. We can observe in average the videos long 17-18 minutes.

<img src="https://github.com/rleonardg/Anlysis_channel_YTB/blob/main/assets/median_duration_videos.png">

### 3. HighLlighted videos 
We cant clearly intedify spikes. However within the 'HowTo and Style' category, videos focused on how to get cheap furniture tend to perform better. For example: 'Mis hijos compran un sofá por 1 euro y lo traen solos', 'Socorrooooo 👀 voy a la tienda de segunda mano y las tentaciones se apoderan de mi',  'MUEBLES A 1€ en la TIENDA de SEGUNDA MANO'

There is also a notable interest in low-cost home makeover. For example:
'Cambio radical de la buhardilla low cost ✨️ mi lugar del olvido  👀' con un 21% ese mes


| Month   | Title | Views | Month Views | % of Month Views | Duration (min) |
|---------|-------|-------|-------------|------------------|----------------|
| 2024-02 | 🟢 Sección hogar en el Action y cosas que utilizo en mi casa 🏡 | 10468 | 40501 | 25.85 | 10.87 |
| 2024-02 | 🟢 SOMOS RICOS ¡Mesa a 0,50€! Tienda de segunda mano ✋️mueble para mis cosas de costura 😃 | 14135 | 40501 | 34.90 | 12.07 |
| 2024-02 | 🟣 Limpiando la casa tras semanas de virus en casa 😷 | 10124 | 40501 | 25.00 | 15.97 |
| 2024-03 | 🟢 Tienda de segunda mano en Bélgica: muchas antigüedades 😃 | 6479 | 14467 | 44.78 | 11.63 |
| 2024-03 | 🟣 Limpio la mini cocina de 8 personas por la noche | 7988 | 14467 | 55.22 | 15.73 |
| 2024-04 | 🟢 Tienda de segunda mano zona de menaje-hogar 😃😍 | 11241 | 18944 | 59.34 | 16.63 |
| 2024-04 | 🔵 Así tenían el armario mis hijos ¿tus hijos lo hacen solos o se lo organizas tu? | 7703 | 18944 | 40.66 | 10.02 |
| 2024-06 | Mis últimas compras Amazon y Ali express🛍 y otros productos que llevo tiempo usando RECOMENDADO | 3493 | 14359 | 24.33 | 17.60 |
| 2024-06 | Limpiar tapizados con Karcher 🤩 | 10866 | 14359 | 75.67 | 1.02 |
| 2024-07 | Jabón líquido casero para lavadora y multiusos con nueces de lavado y jabón Beltrán 💙 | 2322 | 10774 | 21.55 | 8.67 |
| 2024-07 | Limpiando la cocina y la zona del café ☕️ | 3116 | 10774 | 28.92 | 13.20 |
| 2024-07 | Mis compras en Vinted, a veces triunfas a veces no 😔 | 3271 | 10774 | 30.36 | 4.53 |
| 2024-08 | Que cuesta comprar una propiedad en Marruecos 💰 ya no se puede hablar de nada | 17865 | 76110 | 23.47 | 21.93 |
| 2025-02 | Mis hijos compran un sofá por 1 euro y lo traen solos 😅 | 16172 | 64137 | 25.21 | 11.97 |
| 2025-05 | Socorrooooo 👀 voy a la tienda de segunda mano y las tentaciones se apoderan de mi | 19281 | 90783 | 21.24 | 22.47 |
| 2025-06 | Aunque resisto tentaciones me gasto 128€ en el Action de Holanda 😲 | 13708 | 34832 | 39.35 | 14.03 |
| 2025-06 | Encontrar tesoros valiosos a precio de ganga en la Tienda de segunda mano | 21124 | 34832 | 60.65 | 35.65 |
| 2025-11 | Cambio radical de la buhardilla low cost ✨️ mi lugar del olvido 👀 | 18077 | 83099 | 21.75 | 34.20 |
| 2025-11 | MUEBLES A 1€ en la TIENDA de SEGUNDA MANO | 16676 | 83099 | 20.07 | 15.22 |
| 2026-04 | Sofá de jardín en la basura! 😱 voy a la tienda de segunda mano y compro lo que menos buscaba | 13659 | 44090 | 30.98 | 16.47 |
| 2026-04 | Rincón de cafecito en el jardín por 60€ ‼️ sofá de la basura 😱 | 12598 | 44090 | 28.57 | 20.05 |
| 2026-04 | La decoración de la casa del pueblo de mi madre 👀 | 17833 | 44090 | 40.45 | 11.70 |

### 4. Earns per month
For this case we get the data diretly for a video that the creator upload. The RPM is on average 2,5-3

| Month   | Earn ($) | RPM |
|---------|-------|-------|
| 2025-09 | 1000 | 2,8 |
| 2025-10 | 600 | 2,2 |
| 2025-11 | 500 | 6 |
| 2025-12 | 200 | 2,5 |
| 2026-01 | 450 | 3,7 |
| 2026-02 | 500 | 3,8 |


### 5. Conclusion
* There are not a views grew up significantly per month
* The videos haven't a high post-edit
* Have a 8-5 videos-short ratio and RPM >= 2 makes you not depend of viral videos

## Resources
- [youtube api v3](https://developers.google.com/youtube/v3/docs?hl=es-419)
