# Week 01 — March 23, 2026

## What I set up
- WSL2, Ubuntu, Python, Git, and VS Code all connected and working
- SSH authentication key linked to GitHub
- career-roadmap folder structure created and pushed to GitHub

## What was confusing
- WSL2 and Ubuntu not installing correctly until full computer restart
- SSH agent had to be loaded manually until we automated it in .bashrc

## What clicked
- Ubuntu is a Linux distribution that runs inside Windows via WSL2
- VS Code connects to Ubuntu through the WSL extension
- An SSH key proves my identity to GitHub — private key stays on my machine, public key goes to GitHub. When I push code they are compared and if they match I am verified
- My old projects used HTTPS for authentication, SSH is more secure and professional