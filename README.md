# ProjectNova (UE 5.6, C++)

UE5 C++ учебный проект (шутер от третьего лица), созданный по мотивам курса «Unreal Engine: Полное руководство по C++». Реализованы основные игровые системы: оружие (equip/reload), здоровье/смерть, управление матчем (GameMode/PlayerState), UMG-интерфейсы (HUD, статистика/экран Game Over), команды, AI (Behavior Tree + Perception), сборка и упаковка проекта.

### Генерация файлов проекта (если нужно)
1. Закрой Unreal Editor и Visual Studio
2. ПКМ по `ProjectNova.uproject` → **Generate Visual Studio project files**
3. Открой `ProjectNova.sln`

### Сборка в Visual Studio
1. Конфигурация: **Development Editor**
2. Платформа: **Win64**
3. **Build → Build Solution**
4. Запуск: **Local Windows Debugger** (или открой `.uproject` и собери из UE)