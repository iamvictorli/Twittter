# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'Twittter' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Twittter
  pod 'Alamofire', '~> 4.7'
  pod 'OAuthSwift', '~> 1.2.0'
  pod 'AlamofireImage', '~> 3.4'
  pod 'OAuthSwiftAlamofire'
  pod 'KeychainAccess'
  pod 'DateToolsSwift'
  pod 'TTTAttributedLabel'

end

# Workaround for Cocoapods issue #7606
post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
        config.build_settings.delete('CODE_SIGNING_ALLOWED')
        config.build_settings.delete('CODE_SIGNING_REQUIRED')
    end
end
