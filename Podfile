# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'
platform :ios, '12.0'
use_frameworks!

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings["IPHONEOS_DEPLOYMENT_TARGET"] = "13.0"
    end
  end
end

target 'rosy_elephant-iPad' do
  # Comment the next line if you don't want to use dynamic frameworks

  # Pods for rosy_elephant-iPad
  pod 'SnapKit'
  pod 'Moya', '~> 15.0'
  pod 'Kingfisher', '~> 7.0'
  pod 'SwiftyJSON', '~> 4.0'
  pod 'ObjectMapper', '~> 3.5'
  pod 'SwiftyUserDefaults', '~> 5.0'

  target 'rosy_elephant-iPadTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'rosy_elephant-iPadUITests' do
    # Pods for testing
  end

end
