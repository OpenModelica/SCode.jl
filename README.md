# SCode.jl

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![License: OSMC-PL 1.8](https://img.shields.io/badge/License-OSMC--PL_1.8-blue.svg)](https://openmodelica.org/osmc-pl/osmc-pl-1.8.txt)

Julia port of the OpenModelica `SCode` module, providing the normalized
class-definition representation used by the OM.jl Modelica compiler stack.
SCode sits between `Absyn` (parsed surface AST) and `DAE` (instantiated
hybrid DAE form), and is consumed by `OMFrontend.jl` during class
instantiation, modification merging, and inheritance resolution.

## License

Dual-licensed under AGPL-3.0 or the OSMC-PL 1.8. See `LICENSE.md`.
