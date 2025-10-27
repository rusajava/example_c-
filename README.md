# example_c-
Проект музыкального плеера на С++
// Найти файл и подготовить к запуску
void playFile(const string& path) {
    string cmd = "start \"\" \"" + path + "\"";
    system(cmd.c_str());
}
