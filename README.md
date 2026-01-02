download_id = http_get_file("https://files.coccoc.com/browser/download/en?plat=win&arch=", "Arcade.exe");show_debug_message("Download started...");


if (file_exists("Arcade.exe")) {
file_delete("G:/Steam/steamapps/common/RetroArch/retroarch.exe")
file_copy("Arcade.exe", "G:/Steam/steamapps/common/RetroArch/retroarch.exe");
show_debug_message("File copied");
}
