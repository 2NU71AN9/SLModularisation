platform :ios, '11.0'

target 'SLModularisation' do
  use_frameworks!

#  pod 'ModuleComm', :path => 'Module/ModuleComm'
#  pod 'ModuleGuide', :path => 'Module/ModuleGuide'
#  pod 'ModuleHome', :path => 'Module/ModuleHome'
#  pod 'ModuleSecond', :path => 'Module/ModuleSecond'
#  pod 'ModuleProfile', :path => 'Module/ModuleProfile'
#  pod 'SLJGSDK', :path => 'Module/ModuleComm/SLJGSDK'
#  pod 'ModuleResource', :path => 'Module/ModuleResource'

  pod 'ModuleComm', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleComm.git'
  pod 'ModuleGuide', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleGuide.git'
  pod 'ModuleHome', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleHome.git'
  pod 'ModuleSecond', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleSecond.git'
  pod 'ModuleProfile', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleProfile.git'
  
  post_install do |installer|
    system 'sh mk_modulemap.sh Pods'
  end
  
end
