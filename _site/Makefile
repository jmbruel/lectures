#-----------------------------------------------------
# Some usefull instructions...
#
#-----------------------------------------------------

deploy: 
	@echo "========================================"
	@echo "==> Deploying web site"
	bundle install
	jekyll  build
	git commit -am "deploy"
	git push

clean:
	rm -rf Gemfile.lock
