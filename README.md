welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/LadyMiteSolano/LadyMiteSolano/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

#import java.util.Scanner ;

public class Program
{
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.println ("Este es un test para saber si el te ama.");
        System.out.print("Te gusta? ");
        String r = in.nextLine();
        boolean b, c, d;
        if (r.equalsIgnoreCase("no")){
            b = false;
        } else {
            b = true;
        } 
        System.out.println("Hace cuanto lo conoces? (meses) ");
        r = in.nextLine();
        int time = Integer.parseInt(r);
        if (time > 6 && time < 48){
            c = true;
        } else {
            c =false;
        }
        System.out.println("como te llevas con el? ");
        r = in.nextLine();
        if (r.equalsIgnoreCase("pesimo") || r.equalsIgnoreCase("mal")){
            d = false;
        } else {
            d = true;
        }
        if (b && c && d) {
            System.out.println("Lo siento, solo te ve como amiga :(");
        } else {
            System.out.println("El es feliz con otra, lo lamento princesa.");
        }
    }
}
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LadyMiteSolano/LadyMiteSolano/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
