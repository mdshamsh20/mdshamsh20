<h1 align="center">Hi 👋, I'm Md Shamsuzzama Siddique</h1>
<h3 align="center">About: Software developer with 1.5+ year of experience in developing and maintaining real-world software products using Typescript, Next.js, Tailwind CSS, JavaScript, and React.js. Proven ability to collaborate with a team of experienced engineers to design, implement, and test new features. Seeking a challenging software development role where I can use my skills to build innovative and user-friendly products.</h3>

<p align="center">
  </a>
    <a href="https://twitter.com/intent/tweet?text=Add%20dynamically%20generated%20GitHub%20Trophy%20on%20your%20readme%0D%0A&url=https%3A%2F%2Fgithub.com%2Fryo-ma%2Fgithub-profile-trophy">
    <img src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fryo-ma%2Fgithub-profile-trophy"/>
  </a>
</p>
<p align="center">
  You can use this service for free. I'm looking for sponsors to help us keep up with this service❤️
</p>
<p align="center">
  <a href="https://github.com/sponsors/ryo-ma">
    <img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=ff69b4"/>
  </a>
</p>

# Quick Start

Add the following code to your readme. When pasting the code into your profile's
readme, change the `?username=` value to your GitHub's username.

```
[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma)](https://github.com/ryo-ma/github-profile-trophy)
```

<p align="center">
  <img alig src="https://github-profile-trophy.vercel.app/?username=ryo-ma&column=8&rank=SSS,SS,S,AAA,AA,A,B,C" />
</p>

## Use theme

Add optional parameter of the theme.

```
[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92327052-d99b9e00-f091-11ea-9a24-c7ec86982370.png">
</p>

**[More detail](#apply-theme)**

# About Rank

Ranks are `SSS` `SS` `S` `AAA` `AA` `A` `B` `C` `UNKNOWN` `SECRET`.

| Rank       | Description                                                                                |
| ---------- | ------------------------------------------------------------------------------------------ |
| SSS, SS, S | You are at a hard to reach rank. You can brag.                                             |
| AAA, AA, A | You will reach this rank if you do your best. Let's aim here first.                        |
| B, C       | You are currently making good progress. Let's aim a bit higher.                            |
| UNKNOWN    | You have not taken action yet. Let's act first.                                            |
| SECRET     | This rank is very rare. The trophy will not be displayed until certain conditions are met. |

## Secret Rank

The acquisition condition is secret, but you can know the condition by reading
this code.

<p align="center">
  <img width="110" src="https://user-images.githubusercontent.com/6661165/91643641-28cd4780-ea70-11ea-94a9-a51885252700.png" />
</p>

There are only a few secret trophies. Therefore, if you come up with interesting
conditions, I will consider adding a trophy. I am waiting for contributions.

# About Display details

<p align="center">
  <img width="220" src="https://user-images.githubusercontent.com/6661165/91642962-6333e600-ea6a-11ea-83af-e371e996bfa6.png" />
</p>

1. Title name of aggregation target.
2. Current Rank.
3. Title according to rank.
4. Target aggregation result.
5. Next Rank Bar. The road from the current rank to the next rank.

# Optional Request Parameters

- [title](#filter-by-titles)
- [rank](#filter-by-ranks)
- [column](#specify-the-maximum-row--column-size)
- [row](#specify-the-maximum-row--column-size)
- [theme](#apply-theme)
- [margin-w](#margin-width)
- [margin-h](#margin-height)
- [no-bg](#transparent-background)
- [no-frame](#hide-frames)

## Filter by titles

You can filter the display by specifying the titles of trophy.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Followers
```

<p align="center">
  <img width="110" src="https://user-images.githubusercontent.com/6661165/92317141-80ebe700-f038-11ea-8501-4015bfbb2cf4.png">
</p>

If you want to specify multiple titles.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Stars,Followers
```

## Filter by ranks

You can filter the display by specifying the ranks.\
`Available values: SECRET SSS SS S AAA AA A B C`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S
```

<p align="center">
  <img width="110" src="https://user-images.githubusercontent.com/6661165/91642657-1cdd8780-ea68-11ea-994b-4568a55cd22a.png" />
</p>

If you want to specify multiple ranks.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S,AAA
```

You can also exclude ranks.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=-C,-B
```

## Specify the maximum row & column size

You can specify the maximum row and column size.\
Trophy will be hidden if it exceeds the range of both row and column.

`Available value: number type`\
`Default: column=6 row=3`

Restrict only row

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2
```

Restrict only column

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&column=2
```

Restrict row & column

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2&column=3
```

<p align="center">
  <img width="330" src="https://user-images.githubusercontent.com/6661165/91659474-c07f7400-eb0a-11ea-84f2-eb6b42547829.png">
</p>

Adaptive column

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&column=-1
```

You can set `columns` to `-1` to adapt the width to the number of trophies, the
parameter `row` will be ignored.

## Apply theme

Available themes.

| theme                       |
| --------------------------- |
| [flat](#flat)               |
| [onedark](#onedark)         |
| [gruvbox](#gruvbox)         |
| [dracula](#dracula)         |
| [monokai](#monokai)         |
| [chalk](#chalk)             |
| [nord](#nord)               |
| [alduin](#alduin)           |
| [darkhub](#darkhub)         |
| [juicyfresh](#juicyfresh)   |
| [buddhism](#buddhism)       |
| [oldie](#oldie)             |
| [radical](#radical)         |
| [onestar](#onestar)         |
| [discord](#discord)         |
| [algolia](#algolia)         |
| [gitdimmed](#gitdimmed)     |
| [tokyonight](#tokyonight)   |
| [matrix](#matrix)           |
| [apprentice](#apprentice)   |
| [dark_dimmed](#dark_dimmed) |
| [dark_lover](#dark_lover)   |
| [kimbie_dark](#kimbie_dark) |

### flat

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=flat
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92325601-039b9300-f087-11ea-983a-fce8133549ee.png">
</p>

### onedark

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onedark
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92327052-d99b9e00-f091-11ea-9a24-c7ec86982370.png">
</p>

### gruvbox

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=gruvbox
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92315152-e9c56600-f01c-11ea-9536-1bfbb158cfcb.png">
</p>

### dracula

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dracula
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92490273-c91f2b00-f22b-11ea-9481-b5daae4d7bc3.png">
</p>

### monokai

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=monokai
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/93725426-2c289e80-fbea-11ea-96a4-f6490ccf2126.png">
</p>

### chalk

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=chalk
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/94294003-1de7d300-ff9a-11ea-91d1-60417a4d919b.png">
</p>

### nord

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=nord
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/94346857-7ab2be80-006a-11eb-9082-36d377ae2531.png">
</p>

### alduin

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=alduin
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/99085932-2a88bf00-260c-11eb-9b26-d2f125773831.png">
</p>

### darkhub

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=darkhub
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/102801126-249ab080-43f8-11eb-91c8-f56f94c35777.png">
</p>

### juicyfresh

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=juicyfresh
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/104810094-edbc8c80-5835-11eb-8c20-a76192a00728.png">
</p>

### buddhism

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=buddhism
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/113709167-2412f500-971d-11eb-9ee5-0ab292cf8b4c.png">
</p>

### oldie

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=oldie
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/113709581-a0a5d380-971d-11eb-8583-770dc4091ebf.png">
</p>

### radical

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=radical
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/116633521-adbc8800-a994-11eb-97c4-e45a32721491.png">
</p>

### onestar

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onestar
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/122048400-2af46d00-ce1c-11eb-94e0-c2c6ddaf6819.png">
</p>

### discord

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=discord
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/122048628-7dce2480-ce1c-11eb-9792-1e600b384c4d.png">
</p>

### algolia

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=algolia
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/131685203-92a31101-2d93-4d18-b24a-d81a8bb012c5.png">
</p>

### gitdimmed

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=gitdimmed
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/131685406-799a864f-2691-4840-bb71-1db9c087a507.png">
</p>

### tokyonight

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=tokyonight
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/135482087-27764d6f-53b4-4c2a-8473-32431d12660c.png">
</p>

### matrix

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=matrix
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/31789752/141647414-15cfe279-af12-4746-a886-f494c25c096d.png">
</p>

### apprentice

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=apprentice
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/31789752/144701036-285cdd4b-d687-4ddc-95c2-7ccae9e25a1f.png">
</p>

### dark_dimmed

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dark_dimmed
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/31789752/147340893-655b9fa5-138f-4f29-91ec-2a17c93822d1.png">
</p>

### dark_lover

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dark_lover
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/31789752/152659041-de5b23cb-1be8-4e6b-b07b-726127ab8c3a.png">
</p>

### kimbie_dark

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=kimbie_dark
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/8161064/288417332-408705a4-ae9c-47fe-af1a-9fb08555f526.png">
</p>

## Margin Width

You can put a margin in the width between trophies.\
`Available value: number type`\
`Default: margin-w=0`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&margin-w=15
```

<p align="center">
  <img width="735" src="https://user-images.githubusercontent.com/6661165/93668661-e0ca9f00-fac8-11ea-9bec-325454f49fb4.png">
</p>

## Margin Height

You can put a margin in the height between trophies.\
`Available value: number type`\
`Default: margin-h=0`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&margin-h=15
```

## Example layout

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&column=3&margin-w=15&margin-h=15
```

<p align="center">
  <img width="360" src="https://user-images.githubusercontent.com/6661165/93668677-ff309a80-fac8-11ea-8ae3-3e3e8adbef39.png">
</p>

## Transparent background

You can turn the background transparent.\
`Available value: boolean type (true or false)`\
`Default: no-bg=false`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&no-bg=true
```

<p align="center">
  <img width=660 src="https://user-images.githubusercontent.com/6661165/104810864-ed72c000-583a-11eb-863b-04acffb705ea.png">
</p>

## Hide frames

You can hide the frames around the trophies.\
`Available value: boolean type (true or false)`\
`Default: no-frame=false`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&no-frame=true
```

<p align="center">
  <img width=660 src="https://user-images.githubusercontent.com/6661165/104810887-1d21c800-583b-11eb-8f0d-785c1640dc5d.png">
</p>

# Contribution Guide

Check [CONTRIBUTING.md](./CONTRIBUTING.md) for more details.

# License

This product is licensed under the
[MIT License](https://github.com/ryo-ma/github-profile-trophy/blob/master/LICENSE).
<p align="left"> <img src="https://komarev.com/ghpvc/?username=mdshamsh20&label=Profile%20views&color=0e75b6&style=flat" alt="mdshamsh20" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=mdshamsh20" alt="mdshamsh20" /></a> </p>

- 🔭 I’m currently working at **SettleMint**

- 🌱 I’m currently learning **Kotlin,Solidity,Nodejs etc**

-  All of my personal links are available at [https://linktr.ee/mdshamsuzzama](https://linktr.ee/mdshamsuzzama)
  
- 👨‍💻 All of my portfolio are available at [https://my-portfolio-snowy-xi.vercel.app](https://my-portfolio-snowy-xi.vercel.app)

- 💬 Ask me about **Reactjs,Nextjs,TailwindCss etc**

- 📫 How to reach me **mdshamsuzzama19@gmail.com**

- 📄 Know about my experiences [https://drive.google.com/file/d/1BXrIZ-YeQNUoopBa0vmH7ngj8yEq1gxO/view](https://drive.google.com/file/d/1BXrIZ-YeQNUoopBa0vmH7ngj8yEq1gxO/view)

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://codepen.io/https://codepen.io/mdshamsh20" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codepen.svg" alt="https://codepen.io/mdshamsh20" height="30" width="40" /></a>
<a href="https://twitter.com/mdshamsh736764" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="mdshamsh736764" height="30" width="40" /></a>
<a href="https://linkedin.com/in/https://www.linkedin.com/in/md-shamsuzzama-siddique-baa9a5213/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/md-shamsuzzama-siddique-baa9a5213/" height="30" width="40" /></a>
<a href="https://www.hackerrank.com/@mdshamsuzzama19" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="@mdshamsuzzama19" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.blender.org/" target="_blank" rel="noreferrer"> <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://bulma.io/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/gilbarbara/logos/804dc257b59e144eaca5bc6ffd16949752c6f789/logos/bulma.svg" alt="bulma" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://cloud.google.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://kotlinlang.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://nuxtjs.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/nuxtjs/nuxtjs-icon.svg" alt="nuxtjs" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> <a href="https://vuejs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/> </a> <a href="https://vuetifyjs.com/en/" target="_blank" rel="noreferrer"> <img src="https://bestofjs.org/logos/vuetify.svg" alt="vuetify" width="40" height="40"/> </a> <a href="https://www.adobe.com/products/xd.html" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/adobe-xd.svg" alt="xd" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=mdshamsh20&show_icons=true&locale=en&layout=compact" alt="mdshamsh20" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=mdshamsh20&show_icons=true&locale=en" alt="mdshamsh20" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=mdshamsh20&" alt="mdshamsh20" /></p>
