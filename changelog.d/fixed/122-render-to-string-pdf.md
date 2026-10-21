`render_to_string(pdf: ...)` now returns PDF bytes without setting the controller
response, allowing a subsequent `send_data` call without a DoubleRenderError (#122).
