# jax-rs-example
Example of a getting jax-rs build to work in IntelliJ 16.2

Learned from this that TomcatEE doesn't require the subclass of Application while
Glassfish does.  Looking at the JAX-RS spec and other examples, it seems to be
the only way to do it that is not platform dependent.