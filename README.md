# Matrix Build with Artifacts Workflow

This repository contains a GitHub Actions workflow that demonstrates:

- **Matrix build strategy**: Runs parallel build jobs on multiple OS platforms (`ubuntu-latest`, `macos-latest`, `windows-latest`).
- **Artifact management**: Each build job generates a unique text artifact and uploads it with a naming prefix `build-02f2205-<variant>`.
- **Step identifier**: Each job includes a step with the identifier `matrix-02f2205` for easy tracking.

## Workflow Details

- Runs on every push to the `main` branch.
- Three parallel jobs run on each OS variant.
- Each job creates an output file with the specific OS build details.
- Artifacts are uploaded separately for each variant.

## Usage

You can find the workflow file in `.github/workflows/matrix-build.yaml`.

## Contact

For any questions or issues, contact: 22ds3000113@ds.study.iitm.ac.in

---

Thank you for using this repository!
