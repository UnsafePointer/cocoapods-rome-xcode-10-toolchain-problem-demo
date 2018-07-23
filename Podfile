# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

plugin 'cocoapods-rome', { :pre_compile => Proc.new { |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '4.2'
        end
    end

    installer.pods_project.save
},

    dsym: false,
    configuration: 'Release'
}

target 'RomeTest' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for RomeTest
  pod '1PasswordExtension'
  pod 'AFNetworkActivityLogger'
  # pod 'AFQuickLookViewController'
  pod 'SAMKeychain'
  pod 'Adjust'
  pod 'libextobjc'
  pod 'SocketRocket'
  pod 'BABCropperView'
  pod 'VPInteractiveImageView'
  pod 'FMDB'
  pod 'TLIndexPathTools'
  pod 'JLRoutes'
  pod 'ISO8601DateFormatter'
  pod 'XNGMarkdownParser'
  pod 'Reachability'
  pod 'NoticeView'
  pod 'AFNetworking'
  pod 'DAKeyboardControl'
  pod 'libPhoneNumber-iOS'
  pod 'SDWebImage'
  pod 'TTTAttributedLabel'
  pod 'libsodium'
  pod 'AwesomeMenu'
  pod 'libextobjc'

  target 'RomeTestTests' do
    inherit! :search_paths
    # Pods for testing

    pod 'FBSnapshotTestCase'
    pod 'OCMock'
    pod 'OHHTTPStubs'
    pod 'Expecta'
    pod 'Specta'
  end

end
