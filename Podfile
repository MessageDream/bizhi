source 'https://github.com/CocoaPods/Specs.git'
 
platform :ios, '6.1'
inhibit_all_warnings!
 
xcodeproj 'bizhi'
 
pod 'AFNetworking', '~>2.2'
pod 'SDWebImage', '~>3.6'
pod 'ReactiveCocoa', '~>2.3'
pod 'SVProgressHUD', '~>1.0'
pod 'SVPullToRefresh', '~>0.4'
pod 'ReactiveViewModel', '~>0.1'
pod 'CHTCollectionViewWaterfallLayout', '~>0.4'
pod 'JSONModel', '~>0.13'
pod 'AFNetworking-RACExtensions', '~>0.1'
pod 'Objection', '~> 0.9'

 
post_install do |installer|
  installer.project.targets.each do |target|
    puts "#{target.name}"
  end
end