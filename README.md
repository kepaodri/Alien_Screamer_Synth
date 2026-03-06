# Alien_Screamer_Synth
PCB design for "Alien Screamer" synthesizer (original design by Ray Wilson) in 4-layer stackup using THT components.

# MFOS Alien Screamer Analog Noise Box

The **Alien Screamer** is a classic lo-fi analog synthesizer designed by Ray Wilson of *Music From Outer Space*. It serves as an excellent introductory project for synth-DIY enthusiasts, providing a hands-on way to learn about oscillators, modulation, and integrated circuit amplification.

---

## 🚀 Features
* **Wide-Range VCO:** A ramp-core oscillator driven by an exponential V-to-I converter, capable of frequencies from sub-audio clicks to 10kHz.
* **Integrated LFO:** A square-wave oscillator with adjustable rate and depth.
* **Waveform Shaping:** Toggle between square, low-pass filtered, and differentiated "tweet" waveforms for diverse modulation.
* **Sync Effects:** Hard-sync capability where the LFO resets the VCO for aggressive, complex timbres.
* **Built-in Audio:** Includes an LM386-based 1W amplifier and internal speaker for portability.
* **Battery Powered:** Optimized for low current draw (~10mA) on a single 9V battery.
* **Kludge Area:** The PCB layout includes a dedicated prototyping space for custom circuit modifications.

---

## 🛠 Technical Specifications

| Requirement | Details |
| :--- | :--- |
| **Core ICs** | LM324 (Quad Op-Amp), LM386 (Audio Amp) |
| **Power Supply** | 9V Battery (Approx. 10mA draw) |
| **Oscillators** | 1 VCO (Exponential), 1 LFO |
| **Output** | Internal Speaker + 1/4" Line Out Jack |
| **Control Inputs** | VCO Freq, LFO Rate, LFO Depth, Volume |
| **Switches** | Power, Waveform Select, LFO Sync |

---

## 📂 Project Structure
* `schematics/` - Original circuit diagrams and signal flow.
* `bom/` - Bill of Materials (BOM) for component sourcing.
* `pcb/` - Design files and layout templates.
* `docs/` - Wiring diagrams and assembly instructions.

---

## 🛸 Sound Capabilities
The Alien Screamer excels at creating experimental textures, including:
* **Sci-Fi Effects:** Star Trek-style communicator chirps and saucer sounds.
* **Nature Mimicry:** Bird tweets and insect-like modulations.
* **Performance:** Theremin-like glissandos and thundering drones.

> **Note:** This project is designed for educational and DIY purposes. Original design by Ray Wilson (Music From Outer Space).

