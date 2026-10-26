# Ad Astra StellarView Compatibility

Disables Ad Astra custom sky and configures StellarView for every planet.

## Dependencies

<table>
  <tbody>
    <tr>
      <td>StellarView Mixin Renderer</td>
      <td>&nbsp;&nbsp;&nbsp;&nbsp;</td>
      <td>
        <a href="https://github.com/lukaskabc/StellarViewMixinRenderer/">
          <img src="https://img.shields.io/badge/GitHub-grey?style=for-the-badge&logo=GitHub" alt="GitHub">
        </a>
      </td>
      <td>
        <a href="https://modrinth.com/mod/stellar-view-mixin-renderer">
          <img src="https://img.shields.io/badge/Modrinth-grey?style=for-the-badge&logo=modrinth" alt="Modrinth">
        </a>
      </td>
      <td>
        <a href="https://curseforge.com/minecraft/mc-mods/stellar-view-mixin-renderer">
          <img src="https://img.shields.io/badge/CurseForge-grey?style=for-the-badge&logo=curseforge" alt="CurseForge">
        </a>
      </td>
    </tr>
    <tr>
      <td>Ad Astra</td>
      <td></td>
      <td>
        <a href="https://github.com/terrarium-earth/Ad-Astra">
          <img src="https://img.shields.io/badge/GitHub-grey?style=for-the-badge&logo=GitHub" alt="GitHub">
        </a>
      </td>
      <td>
        <a href="https://modrinth.com/mod/ad-astra">
          <img src="https://img.shields.io/badge/Modrinth-grey?style=for-the-badge&logo=modrinth" alt="Modrinth">
        </a>
      </td>
      <td>
        <a href="https://curseforge.com/minecraft/mc-mods/ad-astra">
          <img src="https://img.shields.io/badge/CurseForge-grey?style=for-the-badge&logo=curseforge" alt="CurseForge">
        </a>
      </td>
    </tr>
    <tr>
      <td>StellarView</td>
      <td></td>
      <td>
        <a href="https://github.com/Povstalec/stellarview/">
          <img src="https://img.shields.io/badge/GitHub-grey?style=for-the-badge&logo=GitHub" alt="GitHub">
        </a>
      </td>
      <td>
        <a href="https://modrinth.com/mod/stellarview">
          <img src="https://img.shields.io/badge/Modrinth-grey?style=for-the-badge&logo=modrinth" alt="Modrinth">
        </a>
      </td>
      <td>
        <a href="https://curseforge.com/minecraft/mc-mods/stellarview">
          <img src="https://img.shields.io/badge/CurseForge-grey?style=for-the-badge&logo=curseforge" alt="CurseForge">
        </a>
      </td>
    </tr>
  </tbody>
</table>

## Implemented planets/dimensions
- Earth (overworld)
- Earth Orbit
- Mars
- Mars Orbit
- Mercury
- Mercury Orbit
- Moon 
- Moon Orbit
- Glacio
- Glacio Orbit
- Venus Orbit

Venus is not included because the planet has dense atmosphere and sky is not visible.

## The used numbers

- Earth Orbit
  - The first idea was to use the [ISS](https://en.wikipedia.org/wiki/International_Space_Station) orbit. 
However, because the station is so close to Earth, the in-game immersion from looking at few huge pixels of the Earth texture is not great.
  - The Earth orbit dimension is set to orbit at `26 571` km from the center of Earth.
  - [GPS satellites](https://www.gps.gov/space-segment) are in medium Earth orbit at ~`20 200` km above sea level (plus [Earth radius](https://en.wikipedia.org/wiki/Earth_radius) `6 371`km gives `26 571` km)
  - This gives the immersion similar to original Ad Astra while also using a real number.
- Lunar Orbit
  - Tha orbit around the Moon is `20 000` km, which is the upper bound of [high lunar obit](https://en.wikipedia.org/wiki/Lunar_orbit#Lunar_high_orbits).


- Orbit speeds are set to Minecraft day, although the Sun is not aligned with the day-light cycle, setting higher speeds could cause nausea for certain users.

## Notes
The planets are configured in the same way as for Stellaris compatibility

<a href="https://github.com/lukaskabc/Stellaris-StellarView-Compatibility">
  <img src="https://img.shields.io/badge/Stellaris_Compatibility-grey?style=for-the-badge&logo=GitHub" alt="GitHub">
</a>