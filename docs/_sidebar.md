docs/
├── index.md                          ← Homepage
├── 01-introduction.md                ← Parent (has_children: true)
├── 01-introduction/
│   ├── about.md                      ← Child (parent: Introduction)
│   ├── glossary.md                   ← Child (parent: Introduction)
│   └── revision-history.md           ← Child (parent: Introduction)
├── 02-hardware.md                    ← Parent (has_children: true)
├── 02-hardware/
│   ├── 1_transducer.md               ← Child (parent: Hardware)
│   ├── 2_distribution-box.md         ← Child (parent: Hardware)
│   └── 3_transceiver.md              ← Child (parent: Hardware)
├── 03-system-cabling.md              ← Parent (has_children: true)
├── 03-system-cabling-and-cabling-list/
│   └── cable-list.md                 ← Child (parent: System Cabling)
├── 04-maintenance.md                 ← Parent (has_children: true)
├── 04-maintenance/
│   └── system-health-check.md        ← Child (parent: Maintenance)
├── 05-troubleshooting.md             ← Parent (has_children: true)
├── 05-troubleshooting/
│   └── troubleshooting-and-repairs.md ← Child (parent: Troubleshooting)
├── 06-disassembly-assembly.md        ← Parent (has_children: true)
└── 06-disassembly-and-assembly/
    ├── 1_transceiver-unit.md         ← Child (parent: Disassembly and Assembly)
    ├── 1_transducer-unit.md          ← Child (parent: Disassembly and Assembly)
    └── 2_distribution-box.md         ← Child (parent: Disassembly and Assembly)
