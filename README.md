# OrcaSlicer Profiles — Creality Ender-3 V3 KE

Perfis otimizados do OrcaSlicer para Creality Ender-3 V3 KE com firmware Klipper.

## 📋 Conteúdo

- **9 perfis de filamento**: MasterPrint (PLA, PLA High Speed, PLA Silk, PLA Matte, PETG, TPU) + Voolt3D PA6-CF
- **27 perfis de processo**: Quality, Speed, Mecanica, Cozinha, Escultura, Standard, Draft, Fine, Optimal
- **1 perfil de máquina**: Creality Ender-3 V3 KE 0.4 nozzle (CrealityPrint)

## 🔧 Instalação

1. Baixe os arquivos
2. Copie as pastas `filament/`, `machine/` e `process/` para:
   ```
   C:\Users\<seu_usuario>\AppData\Roaming\OrcaSlicer\user\default\
   ```
3. Reinicie o OrcaSlicer

## ✅ Validação

Todas as configurações foram cruzadas com:
- **Documentação oficial MasterPrint** (PLA, PETG, TPU, ABS, ASA)
- **Documentação oficial Voolt3D** (PA6-CF)
- Perfis de sistema do OrcaSlicer (system parents)
- Comunidade Reddit (r/Ender3V3KE, r/klippers)
- DREMC Support guidelines

## ⚠️ Notas Importantes

- **Voolt3D PA6-CF**: Requer bico de aço endurecido (abrasivo), câmara fechada, secar antes @ 60°C/4-12h
- **ABS/ASA**: Requerem enclosure para melhores resultados
- **TPU volumetric speed**: 3.5 mm³/s (limite seguro para Sprite Direct Drive)
- **Pressure Advance**: Configure por filamento na UI do OrcaSlicer

## 📊 Especificações por Fabricante

### MasterPrint
| Material | Nozzle | Bed | Fan | Observações |
|----------|--------|-----|-----|-------------|
| PLA | 180-210°C | 40-60°C | 100% | PLA Premium |
| PLA High Speed | 190-220°C | 55-65°C | 100% | Linha Hyper Speed |
| PLA Silk | 180-220°C | 40-60°C | 80% | Acabamento brilhante |
| PLA Matte | 180-210°C | 40-60°C | 100% | Acabamento fosco |
| PETG | 220-240°C | 70-90°C | 50% | Fan moderada |
| TPU 95A | 200-240°C | 40-60°C | 60% | Direct drive, baixa velocidade |
| ABS | 230-250°C | 90-100°C | 0% | Enclosure obrigatório |
| ASA | 235-260°C | 95-110°C | 0% | Enclosure obrigatório |

### Voolt3D
| Material | Nozzle | Bed | Fan | Observações |
|----------|--------|-----|-----|-------------|
| PA6-CF | 260-280°C | 105-120°C | 0% | Bico aço, câmara fechada, secar 60°C/4-12h |

## 📄 Licença

Uso livre. Contribuições são bem-vindas.

---
*Atualizado em: 30/07/2026*
*Pesquisa: MasterPrint oficial + Voolt3D oficial + Comunidade + Documentação OrcaSlicer*