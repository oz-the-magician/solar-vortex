# Solar Vortex

**Live:** https://oz-the-magician.github.io/solar-vortex/

A single-page canvas experience: the Sun flies through the Galaxy at ~230 km/s while the planets trace spirals around it — and you can zoom out, one order of magnitude at a time, from planetary orbits to the edge of the observable universe.

## Levels

| Level | Scale | What you see |
|---|---|---|
| Earth and Moon | ~1 million km | Shaded Earth and the Moon in its real phase for the chosen date |
| Solar System | ~60 AU | 8 planets, spiral trails, orbits; asteroid and Kuiper belts, Ceres, Pluto, Eris, Halley's Comet |
| Nearest stars | ~12 ly | 14 real neighbours (Alpha Centauri, Sirius, Barnard's Star…) |
| Milky Way | ~100 000 ly | 4-arm spiral, bar, dust lanes, Sgr A*, "you are here" |
| Local Group | ~10 Mly | Andromeda, Triangulum, Magellanic Clouds and 8 more galaxies |
| Laniakea | ~520 Mly | Golden flow lines draining into the Great Attractor |
| Laniakea's neighbours | ~1–2 Gly | Shapley, Perseus–Pisces, Coma and Hercules basins |
| Cosmic web | ~10 Gly | Filaments, voids and hundreds of small basins |
| Observable universe | 46.5 Gly radius | Cosmic web inside the CMB sphere |

## Controls

- **Drag** — orbit the camera, **wheel / pinch** — zoom across all levels
- **Click** any planet, star, galaxy or cluster — info card
- **▶ Journey** — a ~45 s guided zoom-out to the edge of the universe and a 2 s hyperjump back
- **Zoom in** on a planet's card — fly to it and see its moons (Galilean moons of Jupiter, Titan)
- **Date** — planets move to their real positions for any day; **Today** resets it
- Toggles: real distances, flight through the galaxy, trails, orbits, names, flows, glow, sound
- **Languages:** English, Czech and Russian — picked from the browser language, switchable with RU / EN / CS

## What is real and what is modelled

- **Real:** planet distances, periods and positions on any date (1800–2200), the Sun's speed and the 60° tilt between the ecliptic and the galactic plane, positions of the nearest stars, directions and distances to Local Group galaxies, clusters and attractors, size of the observable universe. The scene is oriented to the real sky: the Sun flies toward Cygnus, the Galactic centre lies in Sagittarius.
- **Also real:** the Moon's position and phase, orbits of Ceres, Pluto, Eris and Halley's Comet. Earth, the Moon and planets seen up close are drawn 5× larger; Earth's surface is stylised (ocean and clouds, no continents); the starting points of the moons of Jupiter and Saturn are approximate.
- **Modelled:** shape of the Milky Way's arms, filament shapes, Laniakea flow lines (in the spirit of Tully et al. 2014), the cosmic web and its basins, the CMB pattern (Planck-style noise). Object sizes are exaggerated so they stay visible.

## Credits

- Sun plasma, corona and flares adapted from Skill Synapse in [claude-skill-index](https://github.com/oz-the-magician/claude-skill-index) (MIT).
- Laniakea: R. B. Tully, H. Courtois, Y. Hoffman, D. Pomarède, *Nature* 513, 71 (2014).
- No external libraries: plain Canvas 2D and Web Audio. Fonts from Google Fonts.

## License

MIT — see [LICENSE](LICENSE).

---

# Солнечный вихрь

**Сайт:** https://oz-the-magician.github.io/solar-vortex/

Солнце летит сквозь Галактику со скоростью ~230 км/с, а планеты рисуют вокруг него спирали. Начать можно с Земли и Луны, а колесом мыши отъехать от орбит планет до края наблюдаемой Вселенной: Солнечная система → ближайшие звёзды → Млечный Путь → Местная группа → Ланиакея → её соседи → космическая паутина → реликтовое излучение.

**Языки:** английский, чешский и русский — выбираются по языку браузера, переключаются кнопками RU / EN / CS.

**Управление:** перетаскивание вращает камеру, колесо или щипок — масштаб, клик по объекту открывает карточку с фактами. Кнопка «▶ Путешествие» запускает 45-секундный отлёт к краю Вселенной и двухсекундный гиперпрыжок обратно.

**Новое вблизи:** Земля с ночной стороной и Луна в настоящей фазе, пояс астероидов и пояс Койпера, Церера, Плутон, Эрида, комета Галлея, спутники Юпитера и Сатурна (кнопка «Приблизить» в карточке планеты). Земля, Луна и планеты вблизи увеличены в 5 раз, поверхность Земли условная.

**Что реально, а что модель:** расстояния, периоды и положение планет на любую дату (1800–2200), позиции ближайших звёзд, направления и расстояния до галактик и скоплений — по каталогам; сцена повёрнута по настоящему небу: Солнце летит к Лебедю, центр Галактики — в Стрельце. Форма рукавов, нитей, потоков Ланиакеи, космической паутины и узор реликтового излучения — модель. Размеры объектов увеличены, чтобы их было видно.

**Благодарности:** солнце взято из Skill Synapse ([claude-skill-index](https://github.com/oz-the-magician/claude-skill-index)); карта Ланиакеи — Талли и др., *Nature*, 2014.
