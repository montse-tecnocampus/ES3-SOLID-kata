This solution creates an abstract class, Employee, with both attributes. Since we have no context, we don't know if attribute bonus will somehow be used by Engineer, so we left it in the Employee superclass.

If the attribute is irrelevant for Engineer, we could then move it to the subclass.

Other possible solutions would be to make the attributes protected instead of private, and they could be accessed without the need for getters.

Provided solution can be improved since there is no common class (other than an interface containing the <i>payAmount</i> method between Engineer and Manager).