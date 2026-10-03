# Site 3D — CYMA One

Site 3D com scroll para o **CYMA One**, um speaker escultural fictício. Quando o grave cai, a tinta em cima do cone explode numa fonte de arco-íris sobre fundo preto.

Tudo é renderizado em tempo real com WebGL. Cada chapter é um "filme" controlado pelo scroll:

| Chapter | O que acontece |
| --- | --- |
| **Plate** | O speaker de alumínio jateado, e as 15 gotas de tinta em 8 cores caindo no cone |
| **The Drop** | Silêncio, depois um 808 a 32 Hz: o cone dá o soco e a tinta sobe em câmera ultra lenta |
| **Frozen** | O tempo para no pico; a câmera orbita 360° e os chips de paleta recolorem tudo com filtros CSS |
| **Inside** | A câmera voa para dentro da tinta enquanto a frequência varre de 32 Hz a 20 kHz |
| **Anatomy** | O speaker se desmonta em 9 peças, com uma cor diferente explodindo de cada vão |
| **Specs / Buy** | Números com count-up e troca de acabamento (Carbon, Titanium, Sand, Cobalt) |

Também tem: um sampler de cor que lê o frame atual e aplica a cor da tinta na interface, um HUD de espectro, um cursor que espirra tinta e faz splat no clique, e um 808 em Web Audio (o som começa desligado).

## Rodar localmente

```bash
python3 -m http.server 4317
```

Depois abra http://localhost:4317.

Feito com [Three.js](https://threejs.org) e [Lenis](https://lenis.darkroom.engineering). Os dois são carregados de CDN, então não precisa instalar nada.
