## Contributing
Have a look at [community/Corruptor-sample](community/Corruptor-sample) to see a sample folder. Your car should have this same folder structure. Include README.md in your vehicle folder, along with an image (and add the image to the README.md).

Once you've got your folder laid out ready for upload, here's how you can add it to the repo:

1. Download and install [git](https://git-scm.com/) if you don't already have it.
2. Log in to Github and Fork the repo by clicking the Fork button in the top right corner.
3. Click the green `Clone or download` button, and copy the link.
4. Clone the new repo.
   * Windows:
     1. Open any folder in explorer.
	 2. Hold shift and right-click any empty part of the folder.
	 3. Hit either "Open PowerShell window here" or "Open command window here" depending on your version of Windows.
	 4. Type in `git clone ` and paste the link (ctrl+v) and hit enter (full command should look something like `git clone https://github.com/YourName/custom-cars.git`).
	 5. Don't close the window, you'll need it again later.
     <!--* Mac-->
	 <!--* Linux-->
5. When the repo is done being cloned, place your vehicle folder inside the community directory.
6. Go back to the console window and type `cd custom-cars` and hit enter.
7. Type `git add .` and hit enter.
8. Type `git commit -m "Adding my own custom car"` and hit enter (or use whatever message you want after the `-m`).
9. Type `git push origin master` and hit enter.
  * At this point, you will likely be asked to login to Github.
10. Once the push has finished, [create a Pull Request (PR)](https://github.com/Californ1a/custom-cars/compare) and click on `compare across forks`.
11. In the `head repository` drop-down, select `YourName/custom-cars`.
12. Hit the green `Create pull request` button, and then on the next page, the green `Create pull request` button again.
