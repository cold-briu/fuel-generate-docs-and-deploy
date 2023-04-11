# fuel-generate-docs-and-deploy
Custom workflow for fuel guides template

WIP

# Description

1. Takes an md file as input
2. Parses the file into mani mdx files
3. Wire the mdx files into a next js template [see guides template](github.com/cold-briu/fuel-guides-template)
4. Deploys to vercel

# How to

### Secrets url: 
	github.com/$user/$repo/settings/secrets/actions

1. Add VERCEL_ORG_ID secret

		Your "Org ID" is also called your user ID, and it's found at vercel.com/account > settings > general -- at the bottom

2. Add VERCEL_PROJECT_ID secret

		Your "Project ID" is found at vercel.com/dashboard > your project name > settings > general -- at the bottom	
