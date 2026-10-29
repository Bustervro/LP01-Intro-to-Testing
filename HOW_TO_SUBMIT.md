# Finish Learning Practice 01 in GitHub Codespaces

The project has the six required tests in `test/test.ts` and the original `src/functions.ts` is unchanged.

## Run the project

In a GitHub Codespace (or terminal with Node.js installed), open this repository and run:

```bash
npm install
npx jest --version
npm test
```

The Jest test run should report six passing tests. If installation succeeds, take a **real screenshot of the terminal** showing the Jest version. Save it in `screenshot/jest-installed.png`.

## Step 6: Demonstrate a failing test

1. Open `test/test.ts`.
2. In the test `countVowels counts vowels in a string`, temporarily change `.toBe(3)` to `.toBe(300)`.
3. Run `npm test`. The run should show **1 failed and 5 passed tests**.
4. Take a **real screenshot of that terminal result**, and save it as `screenshot/intentional-failure.png`.
5. Change `.toBe(300)` back to `.toBe(3)` and run `npm test` again to confirm all six tests pass.

Keep the screenshots in the repository; do not commit the deliberately incorrect expectation.

## Publish and submit

Upload the project files (including screenshots) to a **public** GitHub repository. If you use Codespaces in the repository, commit and push the changes through Source Control or the terminal:

```bash
git add .
git commit -m "Complete LP01 Jest testing practice"
git push
```

Copy the GitHub repository URL (not the Codespaces URL) and submit it on Canvas.
