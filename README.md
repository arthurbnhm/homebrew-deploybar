# DeployBar Homebrew tap

Install [DeployBar](https://deploybar.com), a native macOS menu bar app for
monitoring Vercel deployments:

```bash
brew install --cask arthurbnhm/deploybar/deploybar
```

Requires macOS 26+ and Apple Silicon. The initial release is an **unsigned
preview**, without Apple Developer ID signing or notarization. Homebrew checks
the archive checksum; it does not remove the need for macOS first-launch approval.
See the [installation guide](https://deploybar.com/#install).

Update with `brew upgrade --cask deploybar`.
The [application source](https://github.com/arthurbnhm/deploybar) and this tap are MIT licensed.
Report vulnerabilities privately through the application's
[security policy](https://github.com/arthurbnhm/deploybar/security/policy).
