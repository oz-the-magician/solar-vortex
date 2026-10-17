# Solar Vortex

**Live:** https://oz-the-magician.github.io/solar-vortex/

A single-page canvas experience: the Sun flies through the Galaxy at ~230 km/s while the planets trace spirals around it — and you can zoom out, one order of magnitude at a time, from planetary orbits to the edge of the observable universe.

## Levels

| Level | Scale | What you see |
|---|---|---|
| Solar System | ~60 AU | 8 planets, spiral trails, orbits; real distances and periods |
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
- Toggles: real distances, flight through the galaxy, trails, orbits, names, flows, glow, sound

## What is real and what is modelled

- **Real:** planet distances and periods, the Sun's speed and 60° tilt, positions of the nearest stars, distances to Local Group galaxies, clusters and attractors, size of the observable universe.
- **Modelled:** shape of the Milky Way's arms, filament shapes, Laniakea flow lines (in the spirit of Tully et al. 2014), the cosmic web and its basins, the CMB pattern (Planck-style noise). Object sizes are exaggerated so they stay visible; the scene's orientation relative to the sky is arbitrary.

## Credits

- Sun plasma, corona and flares adapted from Skill Synapse in [claude-skill-index](https://github.com/oz-the-magician/claude-skill-index) (MIT).
- Laniakea: R. B. Tully, H. Courtois, Y. Hoffman, D. Pomarède, *Nature* 513, 71 (2014).
- No external libraries: plain Canvas 2D and Web Audio. Fonts from Google Fonts.

## License

MIT — see [LICENSE](LICENSE).

---

# Солнечный вихрь

**Сайт:** https://oz-the-magician.github.io/solar-vortex/

Солнце летит сквозь Галактику со скоростью ~230 км/с, а планеты рисуют вокруг него спирали. Колесом мыши можно отъехать от орбит планет до края наблюдаемой Вселенной: Солнечная система → ближайшие звёзды → Млечный Путь → Местная группа → Ланиакея → её соседи → космическая паутина → реликтовое излучение.

**Управление:** перетаскивание вращает камеру, колесо или щипок — масштаб, клик по объекту открывает карточку с фактами. Кнопка «▶ Путешествие» запускает 45-секундный отлёт к краю Вселенной и двухсекундный гиперпрыжок обратно.

**Что реально, а что модель:** расстояния, периоды, позиции ближайших звёзд, галактик и скоплений — по каталогам. Форма рукавов, нитей, потоков Ланиакеи, космической паутины и узор реликтового излучения — модель. Размеры объектов увеличены, чтобы их было видно.

**Благодарности:** солнце взято из Skill Synapse ([claude-skill-index](https://github.com/oz-the-magician/claude-skill-index)); карта Ланиакеи — Талли и др., *Nature*, 2014.
