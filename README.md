# pcie-playground

### Notes
- a minimal PCIe x1 link requires only 9 active signal wires (along with power and GND):
- | Signal Type          | Pins   | Signal Names                |
  |----------------------|--------|-----------------------------|
  | Data (Tx)            | 2      | PETp0, PETn0                |
  | Data (Rx)            | 2      | PERp0, PERn0                |
  | Clock                | 2      | REFCLKp0, REFCLKn0          |
  | Control              | 3      | PERST0#, CLKREQ0#, PEWake0# |
  | Total Active Signals | 9 pins |                             |

