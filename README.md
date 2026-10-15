# XCHECK Static Deployment

A static, responsive XCHECK dashboard that deploys to Vercel or EdgeOne Pages. No Python runtime, server process, API URL, build command, or environment variables are required.

## Deploy to Vercel
1. Create a new GitHub repository and upload all files in this folder to its root.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework preset: **Other**. Build command: leave blank. Output directory: `.` (project root).
4. Deploy.

## Deploy to EdgeOne Pages
Upload this folder / connect the Git repository. Use the project root as the output directory and leave the build command blank.

## Included behavior
- Responsive dashboard and category selector
- Local text input parsing and format validation
- Summary counters, activity log, report export, and copy summary
- No backend required; no input is sent to a server by this page

## Scope
This is a fully working **static interface and local validation tool**, not the original Python account-checking engine. It does not test passwords or attempt sign-ins to third-party services. Such server-side features cannot run on static hosting alone and should only be implemented for authorized systems through a separately deployed, documented API.
