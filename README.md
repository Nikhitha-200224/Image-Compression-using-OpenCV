import cv2

# Read image
image = cv2.imread("input.jpg")

# Compression parameters
compression = [cv2.IMWRITE_JPEG_QUALITY, 50]

# Save compressed image
cv2.imwrite("compressed_image.jpg", image, compression)

print("Image compressed successfully!")
