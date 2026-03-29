MSG ?= Update landing page

deploy:
	cd .. && git add -A && git commit -m "$(MSG)" && git push
	firebase deploy --only hosting
