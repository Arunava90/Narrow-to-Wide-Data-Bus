# Narrow-to-Wide-Data-Bus
This module is designed with valid and ready handshaking signals. A 32-bit narrow data stream enters through the narrow_data pin, and 128-bit wide data is output through the wide_data pin, following the handshaking signals in conjunction with clock and reset signals.

# Brief Introduction
This Verilog module, narrow2wide, performs a narrow-to-wide data bus conversion. The module receives 32-bit data through the narrow_data input, accumulates four such data chunks, and then outputs a 128-bit wide data word through the wide_data output. The design employs valid-ready handshaking signals (narrow_valid, narrow_ready, wide_ready, wide_valid) to ensure proper data transfer synchronization between the narrow and wide interfaces. The conversion process is controlled by a clock signal (clk) and an asynchronous reset signal (rst). Internal registers are use

# Simulation Results
<img width="616" alt="image" src="https://github.com/user-attachments/assets/f5d16095-af16-488f-b951-abc59cdd436d">
<img width="719" alt="image" src="https://github.com/user-attachments/assets/6057fd24-15ac-4552-afe7-6b933069fb79">

<img width="722" alt="image" src="https://github.com/user-attachments/assets/2b062dd9-939a-4b08-a5af-3198e74c4701">
<img width="665" alt="image" src="https://github.com/user-attachments/assets/b69790d4-4203-453a-a411-d5876254b7bd">
<img width="647" alt="image" src="https://github.com/user-attachments/assets/01569c80-6045-459f-afe7-c1f1234b5c92">



