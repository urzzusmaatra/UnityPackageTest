# UnityPackageTest
Testing importing Unity assets via package manager

Setup:
The following line needs to be added to your Packages/manifest.json file in your Unity Project under the dependencies section: "com.rile.extras": "https://github.com/urzzusmaatra/UnityPackageTest.git#master".

Notes:
Unity makes extra care if meta files for all files is created (README.mb didn't have and importing without caused and error)
package.json is a must for import
