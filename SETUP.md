# Apply the GitHub profile README update

1. Open the `AdityaVerma126/AdityaVerma126` profile repository.
2. Replace the repository's root `README.md` with the supplied `README.md`.
3. Add `.github/workflows/snake.yml` at that exact path.
4. Commit both files to the default branch (`main`).
5. Open **Settings → Actions → General** and ensure **Workflow permissions** allows read and write access to repository contents. Enable GitHub Actions if prompted.
6. Open the **Actions** tab and run **Generate contribution snake** once with **Run workflow**. The workflow also runs every 12 hours.
7. After a successful run, confirm that the `output` branch contains:
   - `github-contribution-grid-snake.svg`
   - `github-contribution-grid-snake-dark.svg`

The profile README uses the light and dark SVGs from that `output` branch. The images will show once the first workflow run succeeds.

## Notes

- The two HEO flowchart images are embedded from the existing `docs/images/` directory in the HEO repository.
- No HEO source files or diagrams need to be moved; the paths are already valid in that repository.
- The profile README only features repositories that were found under the `AdityaVerma126` GitHub account.
