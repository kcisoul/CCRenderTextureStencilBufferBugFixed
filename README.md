# CCRenderTextureStencilBufferBugFixed
Some android devices which do not support "GL_OES_packed_depth_stencil" will draw white box for CCClippingNode. In order to make it work you should make two render buffers for  both stencil buffer and depth buffer. 
