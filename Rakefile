require 'rake'

task :link_all [dotfile:xresources, dotfile:bashrc, dotfile:editorconfig, dotfile:gemrc, dotfile:xinitrc, dotfile:xserverrc, dotfile:xsessionrc, dotfile:zshrc, dotfile:wallpaper, dotfile:wallpapers, dotfile:lynx, dotfile:surf, dotfile:newsboat, dotfile:ncmpcpp, dotfile:mozilla, dotfile:dot_dwm, dotfile:compton, dotfile:conky, dotfile:gtk, dotfile:rofi, dotfile:vifm]

namespace :dotfile do
  desc "link .Xresources to home"
  task :xresources do
    ln_s "/home/$USER/.dots/.Xresources", "/home/$USER/.Xresources", force: true
  end

  desc "link .bashrc to home"
  task :bashrc do
    ln_s "/home/$USER/.dots/.bashrc", "/home/$USER/.bashrc", force: true
  end

  desc "link .editorconfig to home"
  task :editorconfig do
    ln_s "/home/$USER/.dots/.editorconfig", "/home/$USER/.editorconfig", force: true
  end

  desc "link .gemrc to home"
  task :gemrc do
    ln_s "/home/$USER/.dots/.gemrc", "/home/$USER/.gemrc", force: true
  end

  desc "link .xinitrc to home"
  task :xinitrc do
    ln_s "/home/$USER/.dots/.xinitrc", "/home/$USER/.xinitrc", force: true
  end

  desc "link .xserverrc to home"
  task :xserverrc do
    ln_s "/home/$USER/.dots/.xserverrc", "/home/$USER/.xserverrc", force: true
  end

  desc "link .xsessionrc to home"
  task :xsessionrc do
    ln_s "/home/$USER/.dots/.xsessionrc", "/home/$USER/.xsessionrc", force: true
  end

  desc "link .zshrc to home"
  task :zshrc do
    ln_s "/home/$USER/.dots/.zshrc", "/home/$USER/.zshrc", force: true
  end

  desc "link .wallpaper.jpg to home"
  task :wallpaper do
    ln_s "/home/$USER/.dots/.wallpaper.jpg", "/home/$USER/.wallpaper.jpg", force: true
  end

  desc "link wallpapers folder to home"
  task :wallpapers do
    ln_s "/home/$USER/.dots/wallpapers", "/home/$USER/wallpapers", force: true
  end

  desc "link lynx config folder to home"
  task :lynx do
    ln_s "/home/$USER/.dots/lynx", "/home/$USER/lynx", force: true
  end

  desc "link surf config folder to home"
  task :surf do
    ln_s "/home/$USER/.dots/.surf", "/home/$USER/.surf", force: true
  end

  desc "link newsboat config folder to home"
  task :newsboat do
    ln_s "/home/$USER/.dots/.newsboat", "/home/$USER/.newsboat", force: true
  end

  desc "link ncmpcpp config folder to home"
  task :ncmpcpp do
    ln_s "/home/$USER/.dots/.ncmpcpp", "/home/$USER/.ncmpcpp", force: true
  end

  desc "link mozilla config folder to home"
  task :mozilla do
    ln_s "/home/$USER/.dots/.mozilla", "/home/$USER/.mozilla", force: true
  end

  desc "link custom dwm config folder to home"
  task :dot_dwm do
    ln_s "/home/$USER/.dots/.dwm", "/home/$USER/.dwm", force: true
  end

  desc "link compton config to config dir"
  task :compton do
    ln_s "/home/$USER/.config/compton", "/home/$USER/.config/compton", force: true
  end

  desc "link conkyrc to home"
  task :conky do
    ln_s "/home/$USER/.config/conky/openbox.conkyrc", "/home/$USER/.conkyrc", force: true
  end

  desc "link gtk-3.0 config to config dir"
  task :gtk do
    ln_s "/home/$USER/.config/gtk-3.0", "/home/$USER/.config/gtk-3.0", force: true
  end

  desc "link rofi config to config dir"
  task :rofi do
    ln_s "/home/$USER/.config/rofi", "/home/$USER/.config/rofi", force: true
  end

  desc "link vifm config to config dir"
  task :vifm do
    ln_s "/home/$USER/.config/vifm", "/home/$USER/.config/vifm", force: true
  end

end
