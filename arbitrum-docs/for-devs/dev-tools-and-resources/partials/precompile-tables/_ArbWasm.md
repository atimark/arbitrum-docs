<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Solidity interface</th>
      <th>Go implementation</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>activateProgram(address program)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L16"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L31"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Compile a wasm program with the latest instrumentation</td>
    </tr>
    <tr>
      <td>
        <code>stylusVersion()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L23"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L90"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the latest stylus version</td>
    </tr>
    <tr>
      <td>
        <code>codehashVersion(bytes32 codehash)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L27"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L164"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the stylus version that program with codehash was most recently compiled with</td>
    </tr>
    <tr>
      <td>
        <code>codehashKeepalive(bytes32 codehash)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L31"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L54"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Extends a program's expiration date (reverts if too soon)</td>
    </tr>
    <tr>
      <td>
        <code>codehashAsmSize(bytes32 codehash)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L36"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L173"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets a program's asm size in bytes</td>
    </tr>
    <tr>
      <td>
        <code>programVersion(address program)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L40"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L182"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the stylus version that program at addr was most recently compiled with</td>
    </tr>
    <tr>
      <td>
        <code>programInitGas(address program)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L45"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L191"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the cost to invoke the program</td>
    </tr>
    <tr>
      <td>
        <code>programMemoryFootprint(address program)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L52"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L200"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the footprint of program at addr</td>
    </tr>
    <tr>
      <td>
        <code>programTimeLeft(address program)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L56"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L209"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets returns the amount of time remaining until the program expires</td>
    </tr>
    <tr>
      <td>
        <code>inkPrice()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L60"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L96"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the amount of ink 1 gas buys</td>
    </tr>
    <tr>
      <td>
        <code>maxStackDepth()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L64"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L102"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the wasm stack size limit</td>
    </tr>
    <tr>
      <td>
        <code>freePages()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L68"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L108"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the number of free wasm pages a tx gets</td>
    </tr>
    <tr>
      <td>
        <code>pageGas()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L72"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L114"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the base cost of each additional wasm page</td>
    </tr>
    <tr>
      <td>
        <code>pageRamp()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L76"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L120"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the ramp that drives exponential memory costs</td>
    </tr>
    <tr>
      <td>
        <code>pageLimit()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L80"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L126"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the maximum initial number of pages a wasm may allocate</td>
    </tr>
    <tr>
      <td>
        <code>minInitGas()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L85"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L132"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the minimum costs to invoke a program</td>
    </tr>
    <tr>
      <td>
        <code>initCostScalar()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L89"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L140"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the linear adjustment made to program init costs</td>
    </tr>
    <tr>
      <td>
        <code>expiryDays()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L93"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L146"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the number of days after which programs deactivate</td>
    </tr>
    <tr>
      <td>
        <code>keepaliveDays()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L97"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L152"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the age a program must be to perform a keepalive</td>
    </tr>
    <tr>
      <td>
        <code>blockCacheSize()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L101"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L158"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Gets the number of extra programs ArbOS caches during a given block.</td>
    </tr>
  </tbody>
</table>
<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Solidity interface</th>
      <th>Go implementation</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>ProgramActivated</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L103"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L50"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Emitted when activating a WASM program</td>
    </tr>
    <tr>
      <td>
        <code>ProgramLifetimeExtended</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/61204dd455966cb678192427a07aa9795ff91c14/src/precompiles/ArbWasm.sol#L110"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v3.1.0/precompiles/ArbWasm.go#L66"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Emitted when extending the expiration date of a WASM program</td>
    </tr>
  </tbody>
</table>