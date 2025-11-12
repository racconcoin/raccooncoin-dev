# raccooncoin-dev
# 🦝 RaccoonCoin 

RaccoonCoin is the reference implementation of the **RaccoonCoin** protocol — an open, community-driven digital currency project.

This software is released under the terms of the **MIT License**.
See the [`COPYING`](./COPYING) file or [opensource.org/licenses/MIT](https://opensource.org/licenses/MIT) for full license details.

---

## Development Process
The `master` branch is continuously built and tested but not guaranteed to be fully stable.
Stable releases are created from dedicated release branches and tagged accordingly.

### GUI Development
The graphical interface is developed separately in
👉 [https://github.com/racooncoin-project/gui](https://github.com/racooncoin-coin-gui). This is a private one

* The GUI repository’s `master` branch is identical across all monotree repos.
* No release branches or tags exist for GUI; please **do not fork it** unless you are contributing to GUI development.

### Contribution Workflow

Before submitting pull requests, please review:

* [`CONTRIBUTING.md`](./CONTRIBUTING.md) — workflow and submission guidelines
* [`doc/developer-notes.md`](./doc/developer-notes.md) — build, test, and code style notes

For complex or controversial changes, discussions should happen on the **developer mailing list** before coding begins.

**Developer IRC:** `#racooncoin-dev` on Freenode

---

## Testing

Testing and peer review are critical to RaccoonCoin’s security.
Please be patient — every pull request must undergo code review and testing.
Helping test others’ PRs speeds up the entire development cycle.

### Automated Testing

* Developers are encouraged to write **unit tests** for new and existing code.

* Run tests with:

  ```bash
  make check
  ```

  See `/src/test/README.md` for details.

* **Functional and regression tests** (Python) can be run locally with:

  ```bash
  test/functional/test_runner.py
  ```

* **CI Pipelines** automatically build and test code on Windows, macOS, and Linux for every pull request.

### Manual QA Testing

Major or high-risk changes should be verified by someone other than the original author.
Include a **test plan** in your pull request description if testing isn’t straightforward.

---

## Translations

All translation work is based on **Bitcoin Core’s Transifex** project.
RaccoonCoin periodically imports updated translations from Transifex.

⚠️ We **do not accept** translation pull requests on GitHub — they will be overwritten on the next import.
See the translation process documentation for details.

---

## Community & Communication

* **Website:** [https://raccooncoin.site](https://raccooncoin.site)
* **Developer IRC:** `#racooncoin-dev` on Freenode
* **Mailing list:** Coming soon (`dev@raccooncoin.site`)
* **Security contact:** [security@raccooncoin.site](mailto:security@raccooncoin.site)

---

### ⚡ Security & Responsibility

RaccoonCoin  is a **security-critical** financial system.
Any bug or oversight may cause real monetary loss.
Always follow responsible disclosure practices and respect the project’s contribution and review policies.


