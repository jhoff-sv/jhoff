<h2>👋 Hi there</h2>
<a href="https://www.linkedin.com/in/jos%C3%A9-hoff/" style="text-decoration: none">
    <img src="https://img.shields.io/badge/-Jos%C3%A9%20Hoff-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jos%C3%A9-hoff/" />
</a>
<a href="mailto:joseaugusto.ares@gmail.com" style="text-decoration: none">
    <img src="https://img.shields.io/badge/-joseaugusto.ares@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:joseaugusto.ares@gmail.com" />
</a>

<h2>About me</h2>

```PHP
use DeveloperStreetCode;

class JoseHoff extends DeveloperStreetCode {
    /**
     * Constructor class.
     *
     * @param string $name         The name of the developer.
     * @param string $education    The educational background of the developer.
     * @param array  $languages    The languages the developer is proficient in.
     * @param array  $technologies The technologies the developer uses.
     * @param array  $tools        The tools the developer uses.
     * @param array  $skills       The skills the developer possesses.
     */
    public function __construct(
        string $name         = 'José Hoff',
        string $education    = 'Self-taught graduate in Street Code',
        array  $languages    = ['pt_BR', 'en_US'],
        array  $technologies = [],
        array  $tools        = [],
        array  $skills       = ['Web Development'],
    ) {
        $this->setTechnologies();
        $this->setTools();
    }

    /**
     * Set the technologies.
     */
    protected function setTechnologies(): void {
        $this->technologies = [
            'CMS'       => ['Roots Sage' ,'WordPress'],
            'framework' => ['Laravel'],
            'language'  => ['CSS', 'JavaScript', 'PHP', 'Python'],
            'OS'        => ['Linux', 'Windows'],
        ];
    }

    /**
     * Set the tools.
     */
    protected function setTools(): void {
        $this->tools = [
            'code'             => ['VSCode', 'Sublime Text'],
            'containerization' => ['Docker'],
            'database'         => ['MySQL', 'SQL'],
            'design'           => ['Adobe XD', 'Figma'],
            'versioning'       => ['Git'],
            'server'           => ['Apache', 'Nginx'],
        ];
    }
}
```
