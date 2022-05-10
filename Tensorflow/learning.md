`with tf.GradientTape() as tape`
returns a context manager that can be used to calculate a list of gradients with restpect to parameters.

`tape.gradient(loss,<list of parameters>)`
returns a list of gradients

`param.assign_sub(lr*gradient)`
equivalent to `param -= lr*gradient`
# will this change be pickedup ?



