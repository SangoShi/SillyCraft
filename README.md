<div align="center">

<img src=".github/assets/logo.svg" alt="SillyCraft" width="160">

# SillyCraft

### Собирай модпаки словами, а не руками

Десктоп-приложение, где ты описываешь идею сборки обычным текстом,<br>
а ИИ подбирает моды, шейдеры и ресурспаки под версию Minecraft и загрузчик.

<br>

<a href="https://sangoshi.github.io/SillyCraft/"><img src="https://img.shields.io/badge/САЙТ-sillycraft-DD7FA1?style=for-the-badge&labelColor=2B0716" alt="Сайт"></a>
<a href="https://github.com/SangoShi/SillyCraft/releases"><img src="https://img.shields.io/badge/СКАЧАТЬ-скоро-94083C?style=for-the-badge&labelColor=2B0716" alt="Скачать"></a>

<img src="https://img.shields.io/badge/версия-0.1.0--alpha-F6BBD0?style=flat-square&labelColor=2B0716" alt="Версия">
<img src="https://img.shields.io/badge/Windows-10%20%2F%2011-DD7FA1?style=flat-square&labelColor=2B0716" alt="Windows">
<img src="https://img.shields.io/badge/Tauri-React-94083C?style=flat-square&labelColor=2B0716" alt="Tauri + React">
<img src="https://img.shields.io/badge/цена-бесплатно-5fba38?style=flat-square&labelColor=2B0716" alt="Бесплатно">

</div>

<br>

> [!NOTE]
> Проект в стадии **alpha**. Первая сборка для Windows скоро появится в [Releases](https://github.com/SangoShi/SillyCraft/releases).

<br>

## Как это выглядит

```text
Ты:          Хочу магическое выживание на Fabric 1.21, среднее по размеру, с шейдерами

SillyCraft:  Готовлю план… Botania, Ars Nouveau, Iris Shaders, Sodium и ещё 24 мода.
             Зависимости разрешены, перевод на русский включён. Ставим в Prism Launcher?

Ты:          Да!

SillyCraft:  ✓ Готово! «Магия 1.21» уже в Prism Launcher.
```

Никаких вкладок с вики, ручного поиска совместимых версий и сломанных зависимостей. Просто разговор.

<br>

## Возможности

<table>
<tr>
<td width="50%" valign="top">

### ✦ AI-сборка
Опиши идею обычными словами — ИИ составит план модов и объяснит, зачем нужен каждый. Лишнее можно удалить, своё — добавить.

</td>
<td width="50%" valign="top">

### ✦ Modrinth внутри
Моды, шейдеры, ресурспаки и датапаки — поиск прямо в приложении, без браузера.

</td>
</tr>
<tr>
<td valign="top">

### ✦ Библиотека сборок
Импорт, редактирование списка модов, иконки и описания. Экспорт в `.mrpack`, `.zip` или `.json` в один клик.

</td>
<td valign="top">

### ✦ Авто-перевод
Перевод модов на русский прямо во время сборки.

</td>
</tr>
<tr>
<td valign="top">

### ✦ Установка в лаунчер
Приложение само находит установленные лаунчеры. Один клик — и сборка уже там.

</td>
<td valign="top">

### ✦ 4 загрузчика
Версия загрузчика выбирается вручную или автоматически под версию игры.

</td>
</tr>
</table>

<br>

## Как это работает

| Шаг | | |
|:---:|---|---|
| **1** | **Опиши идею** | Стиль, режим игры и примерное число модов |
| **2** | **Проверь план** | ИИ объяснит выбор — удали лишнее, добавь своё |
| **3** | **Собери** | Скачивание с Modrinth и разрешение зависимостей |
| **4** | **Играй** | Сборка появится в лаунчере. С переводом |

<br>

## Поддержка

<div align="center">

**Загрузчики**

<img src="https://img.shields.io/badge/Fabric-DD7FA1?style=for-the-badge" alt="Fabric">
<img src="https://img.shields.io/badge/Forge-f7c948?style=for-the-badge" alt="Forge">
<img src="https://img.shields.io/badge/NeoForge-38c8dc?style=for-the-badge" alt="NeoForge">
<img src="https://img.shields.io/badge/Quilt-5fba38?style=for-the-badge" alt="Quilt">

**Лаунчеры**

<img src="https://img.shields.io/badge/Prism_Launcher-2B0716?style=for-the-badge" alt="Prism Launcher">
<img src="https://img.shields.io/badge/ATLauncher-2B0716?style=for-the-badge" alt="ATLauncher">
<img src="https://img.shields.io/badge/Modrinth_App-2B0716?style=for-the-badge" alt="Modrinth App">
<img src="https://img.shields.io/badge/CurseForge-2B0716?style=for-the-badge" alt="CurseForge">
<img src="https://img.shields.io/badge/MultiMC-2B0716?style=for-the-badge" alt="MultiMC">

</div>

<br>

## Установка

1. Скачай последнюю версию из [Releases](https://github.com/SangoShi/SillyCraft/releases).
2. Запусти установщик.
3. Опиши свою первую сборку — и играй.

<br>

## Стек

- **[Tauri](https://tauri.app/)** — лёгкое и быстрое десктоп-приложение
- **[React](https://react.dev/)** — интерфейс
- **[Modrinth API](https://docs.modrinth.com/)** — каталог модов, шейдеров и ресурспаков

<br>

## Структура репозитория

```text
SillyCraft/
├── docs/        # сайт проекта (GitHub Pages)
└── ...          # исходный код приложения
```

<br>

---

<div align="center">

Сделано с 💗 для майнкрафтеров

<sub>SillyCraft — неофициальный проект. Не аффилирован с Mojang Studios или Microsoft.<br>Minecraft — товарный знак Mojang Studios.</sub>

</div>
