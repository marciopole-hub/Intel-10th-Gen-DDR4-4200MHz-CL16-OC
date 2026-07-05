<img width="2559" height="1439" alt="Do github" src="https://github.com/user-attachments/assets/cc4e7a55-7c96-4294-998e-6ea53c7d4e96" />
# Intel-10th-Gen-DDR4-4200MHz-CL16-OC
Intel 10th-Gen DDR4 4200MHz CL16 OC 
# Intel Core i5-10600KF @ 5.1GHz + DDR4 4200MHz CL16 Overclock & Undervolt

Kompletny, wysoce zoptymalizowany profil podkręcania procesora oraz pamięci RAM DDR4 na platformie Intel Comet Lake (10. Generacja). Wynik osiągnięty przy pełnym obsadzeniu wszystkich 4 banków pamięci (4x8GB Single Rank), co pozwala na wykorzystanie funkcji Rank Interleaving (efektywna praca w trybie Dual Rank).

## 🖥️ Specyfikacja sprzętowa (Hardware Specs)
* **CPU:** Intel Core i5-10600KF (Comet Lake-S, Q0)
  * *Core Clock:* 5100 MHz (5.1 GHz) – Overclock 24%
  * *North Bridge / Ring Clock:* 4800 MHz (4.8 GHz)
* **Motherboard:** MSI MPG Z490 GAMING PLUS (6-layer PCB, BIOS vA.F1)
* **RAM:** 4x8GB G.Skill Ripjaws V / Trident Z (Samsung B-Die)
  * *Oryginalny profil bazy:* DDR4-4000 CL17-17-17-37 @ 1.35V

## ⚙️ Stabilne timingi i konfiguracja (Timings & Subtimings)
* **Frequency:** 4200 MHz (Rzeczywiste 2100 MHz, tryb synchroniczny 1:1)
* **Command Rate (CR):** 2T
* **Primary Timings:** CL16-16-16-36
* **tRFC:** 374 (tRFC2: 278 | tRFC4: 171)
* **tREFI:** 65535 (Maksymalna wydajność / Max Performance)
* **Subtimings:** tRRD_S: 4 | tRRD_L: 4 | tFAW: 16 | tRDWR: 12-12-12-13

### ⚡ Monitorowane Napięcia (HWiNFO Voltage Readouts):
* **Vcore:** 1.346 V
* **DRAM Voltage:** 1.464 V
* **CPU VCCIO (Undervolt):** 1.294 V
* **CPU VCCSA (Undervolt):** 1.354 V

## 📊 Wyniki wydajności AIDA64 (AIDA64 Benchmark Results)
Mocny docisk timingów oraz wysokie taktowanie Ring (4.8 GHz) pozwoliły na osiągnięcie świetnych przepustowości:
* **Read (Odczyt):** 63 160 MB/s
* **Write (Zapis):** 65 410 MB/s
* **Copy (Kopiowanie):** 59 449 MB/s
* **Latency (Opóźnienie):** **41.6 ns**

## 🩺 Stabilność i Temperatury (Stability & Thermal Proof)
Profil przeszedł pełną procedurę sprawdzania stabilności w programie **TestMem5 (profil Extreme@anta777)** z końcowym wynikiem **Errors: 0**.

Dzięki precyzyjnemu undervoltingowi magistrali SA/IO, temperatury czterech ciasno ułożonych modułów RAM podczas pełnego obciążenia ustabilizowały się w bezpiecznym zakresie **42.2°C – 43.7°C**. Pozwoliło to zapobiec błędom termicznym, które są powszechne dla kości Samsung B-Die przy agresywnym tREFI 65535.

---
*Opracował: Maslanka23 / marciopole-hub (05.07.2026)*
