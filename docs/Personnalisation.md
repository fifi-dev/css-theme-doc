## Fichier de Configuration

Pour créer vos propres variables personnalisées, vous devez les définir dans votre fichier "cssTheme.config.js" qui se trouve à la racine de votre projet.

Pour ce faire, voici un exemple de votre fichier cssTheme.config.js :


``` 
const cssThemeConfig = {
  theme: "Barbie",
  customVariable: {
    colors: {
        comment: 'Custom colors',
        white: '#CCCCCC'
    },
    spacing: {
        comment: 'Small spacing',
        smallPadding: '10px 5px',
        smallMargin: '15px 10px'
    },
  }
};

export default cssThemeConfig; 

```

## Commandes

Compilé votre code après chaque personnalisation avec la commande suivante :

    $  cssTheme
