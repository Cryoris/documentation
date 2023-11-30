# PotentialBase

<span id="undefined" />

`PotentialBase(molecule)`

Bases: `qiskit.chemistry.algorithms.pes_samplers.potentials.potential_base.EnergySurfaceBase`, `qiskit.chemistry.algorithms.pes_samplers.potentials.potential_base.VibronicStructureBase`

Class to hold prescribed 1D potentials (e.g. Morse/Harmonic) over a degree of freedom.

## Methods

|                                                                                                                                                                                                                                                                                     |                                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| [`dissociation_energy`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.dissociation_energy#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.dissociation_energy "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.dissociation_energy")                         | Returns the dissociation energy (scaled by ‘scaling’)                                                                      |
| [`eval`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.eval#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.eval "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.eval")                                                                                     | After fitting the data to the fit function, predict the energy at a point x.                                               |
| [`fit`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.fit#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.fit "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.fit")                                                                                         | Fits surface to data                                                                                                       |
| [`get_equilibrium_geometry`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_equilibrium_geometry#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_equilibrium_geometry "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_equilibrium_geometry")     | Get the equilibrium energy.                                                                                                |
| [`get_maximum_trusted_level`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_maximum_trusted_level#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_maximum_trusted_level "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_maximum_trusted_level") | Returns the maximum energy level for which the particular implementation still provides a good approximation of reality.   |
| [`get_minimal_energy`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_minimal_energy#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_minimal_energy "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_minimal_energy")                             | Get the minimal energy.                                                                                                    |
| [`get_num_modes`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_num_modes#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_num_modes "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_num_modes")                                                 | This (1D) potential represents a single vibrational mode                                                                   |
| [`get_trust_region`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_trust_region#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_trust_region "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.get_trust_region")                                     | The potential will usually be well-defined (even if not useful) for arbitrary x so we return a fairly large interval here. |
| [`update_molecule`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.update_molecule#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.update_molecule "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.update_molecule")                                         | Wipe state if molecule changes, and check validity of molecule for potential.                                              |
| [`vibrational_energy_level`](qiskit.chemistry.algorithms.pes_samplers.PotentialBase.vibrational_energy_level#qiskit.chemistry.algorithms.pes_samplers.PotentialBase.vibrational_energy_level "qiskit.chemistry.algorithms.pes_samplers.PotentialBase.vibrational_energy_level")     | Returns the n-th vibrational energy level for a given mode.                                                                |