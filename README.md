
## forked from spring-projects/spring-boot 

记录一些阅读源码后的注解，方便后续查阅。注解放在comment相关branch。

### topics

1. AnnotationConfigApplicationContext的初始化
2. ConfigurationClassPostProcessor的处理，这个类涉及到了：@Configuration，@Component，@Import，@ComponentScan，@Bean等
3. ClassPathXmlApplicationContext的初始化。解析xml文件并注册bean。
4. Configuration注解的实现。
5. @Autowired
6. AOP与EnableAspectJAutoProxy
7. AOP与AnnotationAwareAspectJAutoProxyCreator

