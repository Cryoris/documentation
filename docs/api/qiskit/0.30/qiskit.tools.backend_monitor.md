# qiskit.tools.backend\_monitor

<span id="undefined" />

`backend_monitor(backend)`

Monitor a single IBMQ backend.

**Parameters**

**backend** ([*IBMQBackend*](qiskit.providers.ibmq.IBMQBackend#qiskit.providers.ibmq.IBMQBackend "qiskit.providers.ibmq.IBMQBackend")) – Backend to monitor.

**Raises**

*   **QiskitError** – Input is not a IBMQ backend.
*   [**MissingOptionalLibraryError**](qiskit.aqua.MissingOptionalLibraryError#qiskit.aqua.MissingOptionalLibraryError "qiskit.aqua.MissingOptionalLibraryError") – If qiskit-ibmq-provider is not installed