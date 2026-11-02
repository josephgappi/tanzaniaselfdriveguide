# Tanzania Self Drive Guide

A website providing information and resources for travellers planning self-drive safaris in Tanzania.

## About the Project

Tanzania Self Drive Guide helps travellers explore Tanzania independently by providing information about:

- 4x4 self-drive vehicle rentals
- Tanzania national parks and safari destinations
- Self-drive safari routes and itineraries
- Road conditions and driving tips
- Camping and safari preparation
- Safari costs and fuel stops

## Website

https://tanzaniaselfdriveguide.com/

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Images and other website assets

## Hosting and Deployment

The website is hosted on Namecheap shared hosting.

Deployment is automated using **GitHub Actions** and FTP over explicit FTPS.

### Automatic Deployment

Whenever changes are pushed to the `main` branch, GitHub Actions automatically:

1. Checks out the latest repository code.
2. Connects to Namecheap hosting using GitHub Secrets.
3. Synchronizes website files with the `public_html` directory.

### GitHub Secrets

The deployment workflow uses these GitHub Actions secrets:

- `FTP_SERVER`
- `FTP_USERNAME`
- `FTP_PASSWORD`

Sensitive credentials are stored securely in GitHub Secrets and are not included in this repository.

## Repository Structure

```text
tanzaniaselfdriveguide/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── images and website assets
├── HTML pages
└── README.md
```

## Deployment Status

Website deployment is automated through GitHub Actions.

## Maintainer

Joseph Gappi/ African Clay Safaris Developer