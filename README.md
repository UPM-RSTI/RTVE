# SURI_IDS_MASTER — Práctica IDS con Suricata / Suricata IDS Practice

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/UPM-RSTI/RTVE/blob/main/SURI_IDS_MASTER.ipynb)

---

## 🇪🇸 Español

Práctica de introducción a **Suricata** como motor IDS (Intrusion Detection System), pensada para ejecutarse en remoto desde Jupyter o Google Colab, sin necesidad de una VM propia.

**Aprenderás a:**
- Instalar y configurar Suricata (`suricata.yaml`).
- Capturar tráfico en vivo desde una interfaz de red (opcional).
- Analizar ficheros **PCAP** en modo offline.
- Actualizar reglas con `suricata-update`.
- Interpretar alertas y eventos en `fast.log` y `eve.json`.
- Analizar un caso real: **WannaCry / EternalBlue**.

**Ficheros:**
| Fichero | Descripción |
|---|---|
| `SURI_IDS_MASTER.ipynb` | Versión en español |
| `SURI_IDS_MASTER_EN.ipynb` | Versión en inglés |

**Cómo ejecutar:**
1. Pulsa el badge **"Open in Colab"** de arriba (o abre el notebook directamente en Google Colab).
2. Ejecuta las celdas **en orden**, de principio a fin.
3. Si tu entorno no permite captura de tráfico en vivo, salta esa sección y continúa con el análisis de PCAP offline (es el objetivo principal de la práctica).

**Requisitos:**
- Entorno Linux (Colab o similar) con permisos de `sudo`.
- Conexión a Internet (para instalar Suricata, actualizar reglas y descargar los PCAP de ejemplo).

---

## 🇬🇧 English

Introductory practice on **Suricata** as an IDS (Intrusion Detection System) engine, designed to run remotely from Jupyter or Google Colab — no VM of your own required.

**You will learn to:**
- Install and configure Suricata (`suricata.yaml`).
- Capture live traffic from a network interface (optional).
- Analyze **PCAP** files in offline mode.
- Update rules with `suricata-update`.
- Interpret alerts and events in `fast.log` and `eve.json`.
- Analyze a real-world case: **WannaCry / EternalBlue**.

**Files:**
| File | Description |
|---|---|
| `SURI_IDS_MASTER.ipynb` | Spanish version |
| `SURI_IDS_MASTER_EN.ipynb` | English version |

**How to run:**
1. Click the **"Open in Colab"** badge above (or open the notebook directly in Google Colab).
2. Run the cells **in order**, from start to finish.
3. If your environment doesn't allow live traffic capture, skip that section and continue with the offline PCAP analysis (the main goal of this practice).

**Requirements:**
- A Linux environment (Colab or similar) with `sudo` privileges.
- Internet access (to install Suricata, update rules, and download the sample PCAPs).

---

## License / Licencia

Educational use only / Uso exclusivamente educativo.
