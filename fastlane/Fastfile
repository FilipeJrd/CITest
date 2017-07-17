# More documentation about how to customize your build
# can be found here:
# https://docs.fastlane.tools
fastlane_version "1.109.0"

# This value helps us track success metrics for Fastfiles
# we automatically generate. Feel free to remove this line
# once you get things running smoothly!

default_platform :ios

# Fastfile actions accept additional configuration, but
# don't worry, fastlane will prompt you for required
# info which you can add here later
lane :test do
  scan(
  	clean: true,
  	project: "CITest.xcodeproject",
  	scheme: "CITest",
  	sdk: "iphonesimulator",
  	destination: "name=iPhone 7"
  )
end
