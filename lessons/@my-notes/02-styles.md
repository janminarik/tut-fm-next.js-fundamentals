# CSS module

```ts
import styles from './newissue.module.css'

const NewIssuePage = () => {
  return <h1 className={styles.title}>New issue</h1>
}

export default NewIssuePage
```

# Global CSS

- tema, global.css
- import do root layout

# Tailwind

- velmi vhodne

# Headless CSS

# Radix UI

- nestylovane React komponenty zamerane na pristupnost WAI-ARIA

# Shadcn

- kopirovatelne komponenty posvane na Radix UI a Tailwind CSS
- komponety su plne predstylobane ale customizovatelne
- copy and paste dava zmysel pre customizaciu ale pre udrzbnu je to o hubu
- velmi dobre to moze fungovat s AI nakolko ma pristup k celemu kodu komponentu

# V0 + Shadcn

# Material UI

- skor enterprise sfera
- ma to default Material Design ale ak to potrebujeme customizovat vznikne z toho Frankenstein

# CSS in JS

## Styled components, Emotion

- problem nefunguje s Server Components
